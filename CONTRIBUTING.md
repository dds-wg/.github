# Contributing to DDS

DDS is early-stage and moving fast. All kinds of contributions are welcome, whether you care about decentralized deliberation, open protocols, or building things that matter. You don't need permission to start.

## Principles

- **Lower barriers, not raise them.** If the process confuses you, that's our bug. File an issue.
- **Favor progress over perfection.** We'd rather iterate on something real than debate something theoretical. Protocol changes get careful review; everything else moves fast.
- **Bias toward doing.** Issues, proposals, and PRs are all welcome, whatever gets the conversation started. For protocol changes, an issue first helps align before investing in implementation.

## How to Contribute

### Open an Issue

Issues are for everything: bugs, features, ideas, questions, discussions. At this stage, we want conversation more than structure.

1. Check existing issues first.
2. Open a new issue with a clear title and description.

### Submit Code or Docs

Here is the overall flow:

1. Configure your local Git settings (one-time setup).
2. Fork the repo to your personal GitHub account.
3. Clone your fork locally.
4. Add the upstream remote (one-time setup).
5. Create a feature branch (never push directly to `main`).
6. Do your work: commit and push to your feature branch.
7. Open a **draft** pull request from your branch to upstream `main`.
8. Before each work session, sync your fork's `main` from upstream and rebase your feature branch.

Most of these are one-time setup. The daily loop is just steps 6–8. Below are the details.

#### Local Git Configuration

If this is your first time contributing, configure your local Git settings. This only needs to be done once.

Follow the [Git and GitHub configuration guide](https://github.com/nicobao/personal-notebook/blob/main/002_git_github_config.md). You can use this [`.gitconfig`](https://github.com/nicobao/setup/blob/master/.gitconfig) as a starting point.

Key settings:

- **Commit signing:** Configure a GPG or SSH signing key following the [commit verification guide](https://github.com/nicobao/personal-notebook/blob/main/002_git_github_config.md#gpg-key-and-commit-verification), then [set your `.gitconfig` to always sign](https://github.com/nicobao/setup/blob/master/.gitconfig#L4-L7). See [Signed Commits](#signed-commits) below for why this is required.
- **Pull = rebase:** Configure `pull` to rebase by default instead of merge (we never do merge commits). See [example](https://github.com/nicobao/setup/blob/master/.gitconfig#L25-L26).
- **IMPORTANT: configure your editor for rebase/merge/conflicts:**
  - [Neovim example](https://github.com/nicobao/setup/blob/master/.gitconfig#L9-L15)
  - [VS Code example](https://code.visualstudio.com/updates/v1_70#_3way-merge-editor-improvements)

#### Fork, Clone, and Add Upstream

1. Fork [`dds-wg/dds`](https://github.com/dds-wg/dds) on GitHub.
2. Clone your fork and add the upstream remote:

```bash
git clone git@github.com:<your-username>/dds.git
cd dds
git remote add upstream git@github.com:dds-wg/dds.git
```

Prefer SSH over HTTPS. You can [configure your `.gitconfig` to rewrite HTTPS URLs to SSH automatically](https://github.com/nicobao/setup/blob/master/.gitconfig#L22-L23).

#### Create a Feature Branch

```bash
# Name the branch after yourself and what you're working on
git checkout -b your-username/short-description
```

- Use the pattern `your-username/short-description` (e.g., `nicobao/add-git-workflow`).
- If your work addresses a specific issue, include the issue number: `your-username/42-fix-auth-bug`.
- Never commit directly to `main`.

#### Open a Draft Pull Request

After pushing your feature branch, open a **draft** pull request on GitHub.

- Source: your fork's feature branch. Target: `dds-wg/dds` `main`.
- Draft PRs signal work-in-progress. They let maintainers see what you're doing early, give feedback before you invest too much, and avoid duplicate effort.
- Mark it as ready for review when you're done.

#### Sync Your Fork's Main from Upstream

There are two ways to do this.

**From GitHub:**

Visit your fork on GitHub. Below the "Code" button, click "Sync fork", then "Update branch".

**From the command line:**

```bash
git fetch upstream
git checkout main
git pull                          # sync with your fork's remote (origin)
git pull --rebase upstream main   # pull latest from upstream
# There should be no conflicts since you never push directly to main.
git push --force-with-lease       # push updated main to your fork
```

#### Rebase Your Feature Branch

After syncing `main`, rebase your feature branch onto it. This keeps your branch up to date and your history clean.

```bash
git checkout your-username/short-description

# Make sure all local changes are committed before rebasing.
# Do NOT stash uncommitted changes. Commit them first to avoid
# conflicts when unstashing after the rebase.

git rebase -i origin/main
```

Your editor will open showing your commits. To keep a clean history, mark all commits except the first as `fixup` (or `squash`). This collapses them into one commit, which also means you only resolve each conflict once instead of once per commit. Save and close the editor to proceed.

```bash
# If there are no conflicts, you will see "Successfully rebased...".
# If there ARE conflicts, resolve them with this loop:

git mergetool          # opens your configured editor: resolve, save, quit
git rebase --continue  # if more conflicts remain, repeat; otherwise done
```

After a successful rebase, force-push to your fork. A regular `git push` will fail because you rewrote history. Do NOT pull. Force-push instead:

```bash
git push --force-with-lease
```

This looks like a lot of steps the first time. After doing it once or twice, it becomes muscle memory.

### Commit Messages

We encourage (but don't enforce) commit messages that explain the **why**, not the **what**. The diff shows what changed. Tell us why it matters.

### Signed Commits

All commits must be [signed](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits). Anonymous contributions are not accepted.

To set up commit signing, configure a GPG or SSH signing key. See the [commit verification guide](https://github.com/nicobao/personal-notebook/blob/main/002_git_github_config.md#gpg-key-and-commit-verification) and configure your [`.gitconfig` to always sign](https://github.com/nicobao/setup/blob/master/.gitconfig#L4-L7) so you never forget.

### AUTHORS File

Add your full name and email to the `AUTHORS` file in the repository root when making your first contribution.

## Roles

- **Contributor:** anyone who participates. File an issue, you're a contributor.
- **Maintainer:** earns commit rights through sustained quality contributions. Reviews and merges pull requests.
- **BDFL:** sets the overall vision and project goals; has final authority. Appoints Maintainers, breaks deadlocks.

See [GOVERNANCE.md](GOVERNANCE.md) for the full governance model.

## License

MPL 2.0 (SPDX: `MPL-2.0`)

## Standards

Read and follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions?

See [SUPPORT.md](SUPPORT.md) for where to get help.
