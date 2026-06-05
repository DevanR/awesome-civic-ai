# awesome-civic-ai

A curated, strictly-vetted list of AI tools that support public-interest work — for developers who want to contribute and for journalists and researchers who want to use them. The repo is a README first, a directory of entries second.

## Language

**Entry**:
A single item in the list. Names a project, tool, agent, or scaffold and explains in one or two sentences what it does and why a reader should care. Each entry passes the [[inclusion-gate]] before being added.
_Avoid_: Listing, link, item

**Civic AI**:
AI used in service of public-interest work — across three modes the list treats as equal citizens: AI that powers civic tools (claim verification, FOIA summarization, council-meeting transcription), AI defenses against AI-driven harm (provenance, deepfake forensics, model audits), and reusable agents and scaffolds for civic work.
_Avoid_: AI for good (too vague), ethical AI (different concept — model behavior, not application)

**Public-interest framing**:
How the project presents itself outward. Neutral, non-partisan, oriented around public-interest tech and civic tech rather than any political stance.
_Avoid_: Civic tech (used colloquially but here reserved for the framing layer specifically)

**Motivating crisis**:
The private reason the repo exists — democratic backsliding and the misinformation environment. Lives in maintainer judgment, not in the README's first paragraph. Distinct from [[public-interest-framing]].
_Avoid_: Mission, purpose

**Reader**:
The two people the README is written for: a developer asking "how can I use my skills against this?" and a journalist or researcher asking "what tool helps me do my job?" Every entry must serve at least one of them. Action-oriented — the reader leaves with something to do, not just something to know.
_Avoid_: Audience, user (too generic)

**Use-case category**:
The top-level section of the README. Organized by the harm or problem the entries address (e.g., election integrity, synthetic media, government transparency, source protection, surveillance defense) — not by tool type or audience role.
_Avoid_: Topic, tag

**Inclusion gate**:
The hard criteria an entry must pass before being listed. Strict by design — most PRs are rejected. Specific gates TBD, but include: open source, actively maintained, real users, demonstrably uses AI or defends against AI harm.
_Avoid_: Criteria, rule

**Strict-curated**:
The list's editorial model. Maintainers exercise judgment on every entry; the reader trusts the list because the bar is high. The opposite of an open directory or a tag-based catalog.
_Avoid_: Vetted, moderated

## Flagged ambiguities

**"Civic tech" vs "public-interest tech" vs "tech for good"**:
Used interchangeably in the wild. Inside this repo, [[public-interest-framing]] is the canonical phrase for how we describe ourselves. "Civic tech" is acceptable as a colloquial synonym in entry descriptions. "Tech for good" is avoided — too broad and too marketing-coded.

**Framing vs motivator**:
The repo is publicly framed as neutral public-interest tech, but the [[motivating-crisis]] is specifically democratic backsliding and misinformation. This split is intentional and strategic — neutral framing travels further institutionally. But it creates a real risk: if maintainers forget the motivator, the list drifts into "every civic-tech tool." Maintainers should re-read the motivator before merging.

## Example dialogue

**Maintainer A**: Someone PR'd a police records-management vendor as a civic tech entry.
**Maintainer B**: Does it pass the inclusion gate?
**Maintainer A**: It's open source, maintained, has users. Marketed as public-interest.
**Maintainer B**: But does it serve a reader — a developer wanting to contribute against authoritarian drift, or a journalist? Run it against the motivator.
**Maintainer A**: It's surveillance infrastructure. Reject.
**Maintainer B**: Right. Public-interest framing isn't a free pass; the motivator is the filter.
