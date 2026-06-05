# Strict curation over an open directory

We chose to run `awesome-civic-ai` as a strict-curated list rather than an open, tag-everything directory. Most awesome-lists drift toward the latter over time — entries accumulate, vintage rots, and the signal-to-noise ratio collapses. We're optimizing for the reader who trusts that every entry has been judged worth their time, not for the contributor who wants frictionless inclusion.

## Considered options

- **Open-curated with tags** — low bar, every entry tagged with maintenance status, license, AI mode. Rejected: even with tags, readers don't filter; they scan the top of each section and trust the first few entries. Tags don't fix bad neighbors.
- **Tiered: featured + community** — vetted "Featured" section above a permissive "Community" section. Rejected: two policies double the maintainer cognitive load and the "Community" section becomes a dumping ground that drags down the perceived bar of the whole repo.

## Consequences

- Most PRs will be rejected. CONTRIBUTING.md needs to make this expectation clear up front so contributors aren't surprised.
- Maintainer judgment is the load-bearing element. If maintainers burn out, the list dies — there's no "community moderation" fallback.
- The list will grow slowly. That's a feature; if it's growing fast, we're letting the bar slip.
