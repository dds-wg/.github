# Website Strategy

Planning document for the DDS project website.

## Audiences

1. **Developers** — want to understand the protocol, read the spec, integrate DDS into their tools
2. **Organizations** — want to evaluate DDS for governance, budgeting, or consultation use cases
3. **Community** — want to follow progress, contribute, or join the conversation

## Recommended Stack

**[Astro](https://astro.build/)** — static-first, markdown/MDX native, excellent performance, easy to deploy. Good fit for a spec-heavy project with a blog.

Alternatives considered:
- SvelteKit — more dynamic than we need at launch
- Next.js — heavier, React ecosystem overhead
- Plain HTML — doesn't scale to spec + blog + docs

## Site Structure

```
/              → Hero + elevator pitch + quick links
/spec          → Specification (rendered from markdown in dds monorepo)
/blog          → Blog posts (see strategy-blog.md)
/community     → Links to GitHub, Discord, events, how to contribute
/about         → Mission, team, governance, license info
```

## Design Inspiration

- [zeromq.org](https://zeromq.org/) — clean, developer-focused, bold messaging
- [ucan.xyz](https://ucan.xyz/) — minimal, spec-centric
- [atproto.com](https://atproto.com/) — good balance of technical depth and accessibility

## Hosting

**Cloudflare Pages** or **Vercel** — both have generous free tiers, git-based deploys, good CDN performance.

Decision: defer until we have a domain.

## Open Questions

- [ ] Domain name — `dds.dev`? `dds-wg.org`? `deliberation.protocol`? Something else?
- [ ] Logo and branding — needs design work before launch
- [ ] Spec rendering — build from markdown at deploy time, or maintain separately?
- [ ] Analytics — privacy-respecting option like Plausible, or none at all?

## Timeline

Website launch is not gated on the spec being complete. A landing page with the pitch, links to GitHub, and the blog is enough to start. Target: before DWebCamp July 2026.
