# Blog Strategy

Planning document for the DDS blog.

## Launch Posts

Three posts to establish the project's voice and intent:

1. **"Why Deliberation Needs a Protocol":** The problem. Platform lock-in, data loss, algorithmic manipulation of consensus. Why a protocol-level solution matters.
2. **"Introducing DDS":** The solution. What DDS is, how it works, what it's built on (AT Protocol, Arweave/Filecoin/Logos, Ethereum). The vision.
3. **"Building on AT Protocol":** The technical bet. Why AT Protocol for identity and social infrastructure. What we gain, what we trade off.

## Ongoing Content

- **Design decisions:** "Why we chose X over Y" posts. Show the reasoning, not just the result.
- **Progress updates:** Monthly or milestone-based. What shipped, what's next.
- **Deep dives:** Technical explorations of specific protocol aspects (e.g., archival model, verification layer, deliberation lifecycle).
- **Event reports:** DWebCamp, conferences, meetups.
- **Guest posts:** From contributors, adjacent projects, or domain experts in civic tech / governance.

## Workflow

- Blog posts live as markdown in the `dds` monorepo (under `/blog` or similar).
- New posts are submitted as PRs for review.
- Published via the website build pipeline (Astro or similar).

## Distribution

- **Primary:** DDS website
- **Cross-post:** [WhiteWind](https://whitewind.blog/) (AT Protocol native blogging, dogfooding the ecosystem)
- **Optional:** dev.to, Hacker News, relevant subreddits

## Tone

- Technical but accessible: assume the reader is smart but doesn't know DDS yet
- Opinionated: we have a point of view and we're not afraid to state it
- Show working: share the messy process, not just the polished result
- No corporate speak: write like a person, not a press release

## Frequency

- **First month:** 3 posts (the launch series)
- **Ongoing:** 1-2 posts per month
- **Don't force it.** A good post when there's something to say beats a mediocre post on schedule.
