# Contributing

This list is strictly curated. Most pull requests are rejected. Read this whole file before opening one.

## The inclusion gate

An entry must pass all of these.

**1. AI mode.** The project must clearly fall into one of:
- `[uses-ai]` — AI is a core capability of the tool for public-interest work (not "we use GPT for our docs search")
- `[ai-defense]` — the tool detects, defends against, or provides accountability for AI-driven harms
- `[agent]` — a reusable agent, prompt library, or scaffold for civic work

If you can't put your finger on which mode applies, the entry probably doesn't qualify.

**2. Open source or source-available with a real OSS license.** Closed-source SaaS is out of scope, even if free to use. Source-available licenses (BSL, SSPL, etc.) are case-by-case — explain in your PR.

**3. Actively maintained.** Most recent meaningful commit within the past 6 months. Archived repos and abandoned projects don't make the list.

**4. Real users and a track record.** A weekend hack with a slick README is not enough. We're looking for evidence of use by real journalists, civic technologists, researchers, or organizations.

**5. Serves at least one of our readers.** The README is written for two people: a developer who wants to contribute, and a journalist or researcher who wants to use the tool. If neither would benefit from the entry, it doesn't belong.

**6. Fits the public-interest framing.** Tools marketed as "public-interest" that primarily serve surveillance, policing, or institutional control of citizens are out of scope. Maintainers exercise judgment here.

## Entry format

Place entries under the appropriate use-case section, alphabetized within the section.

```
- [Project Name](https://link) — one-sentence description of what it does and why it matters. `[ai-mode]` `[jurisdiction]`
```

- One sentence. If you need two, the description isn't tight enough.
- Tags at the end, in backticks, ai-mode then jurisdiction.
- Jurisdiction is an ISO country code, `[global]`, or `[multi: US,EU]`-style.

## How to open a PR

1. Read this file.
2. Open an issue first if you're unsure whether the entry fits — saves both of us time vs. a rejected PR.
3. PR title: `Add: [Project Name] to [Section]`
4. PR body: explain in 2–4 sentences how the entry meets each of the six gates above. If you skip this, the PR will be closed without review.
5. One entry per PR. Multiple entries in one PR will be asked to split.

## How to suggest a new section

Open an issue with the title `Section proposal: <name>`. Explain:
- What harm or use-case it covers
- Why the existing sections don't fit
- 3+ entries you'd add to it on day one

New sections are rare. Don't be hurt if we decline.

## What we reject

- Generic civic-tech tools that don't touch AI — try [awesome-civic-tech](https://github.com/topics/civic-tech) instead. We'll send you that link kindly.
- Closed-source SaaS, including ones with "free for non-profits" tiers.
- Single-developer side projects without a real user base.
- Tools that are AI-adjacent ("we have an AI feature roadmap") but not AI-powered today.
- Entries with marketing copy. The description has to say what the tool does, not how transformative it is.

## Maintainer notes

The motivator behind this list lives in `CONTEXT.md`. Before merging, re-read the flagged ambiguity about framing vs. motivator. A tool can be marketed as public-interest and still fail the motivator filter — that's a reject.
