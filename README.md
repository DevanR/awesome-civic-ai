# awesome-civic-ai

> A strictly-curated list of AI tools for public-interest work — for developers who want to contribute and for journalists and researchers who want to use them.

Every entry on this list either uses AI to power public-interest work, defends against AI-driven harms, or provides reusable agents and scaffolds for civic work. Generic civic-tech is out of scope — for that, see [awesome-civic-tech](https://github.com/topics/civic-tech).

We reject most pull requests. That's the point. See [CONTRIBUTING.md](./CONTRIBUTING.md) before opening one.

## Legend

Each entry carries two tags.

**AI mode**
- `[uses-ai]` — the tool uses AI as a core capability for public-interest work
- `[ai-defense]` — the tool detects, defends against, or provides accountability for AI-driven harms
- `[agent]` — a reusable agent, prompt library, or scaffold for civic work

**Jurisdiction**
- ISO country code (`[US]`, `[UK]`, `[BR]`, `[IN]`, etc.) — applicable primarily in one jurisdiction
- `[global]` — works across jurisdictions
- `[multi: US,EU]` — multiple specific jurisdictions

## Contents

- [Election integrity & voting](#election-integrity--voting)
- [Synthetic media & provenance](#synthetic-media--provenance)
- [Government transparency](#government-transparency)
- [Journalism & source protection](#journalism--source-protection)
- [Surveillance & civil-liberties defense](#surveillance--civil-liberties-defense)
- [Civic AI agents & scaffolds](#civic-ai-agents--scaffolds)

---

## Election integrity & voting

Tools that support free and fair elections, voter education, ballot tracking, election observation, and claim verification during election cycles.

- [Meedan Check](https://meedan.org/check) — collaborative media-verification platform with multilingual AI for analyzing claims across messaging apps and social media. Used by AFP, Rappler, Boom, India Today, and 100+ fact-checking partners across 34 languages. `[uses-ai]` `[global]`

<!-- Seed entries pending maintainer review — propose additions via PR per CONTRIBUTING.md -->

## Synthetic media & provenance

Detection, watermarking, content credentials, deepfake forensics, and provenance tooling for verifying media authenticity.

- [c2pa-rs](https://github.com/contentauth/c2pa-rs) — Rust SDK for the C2PA content-provenance specification: creates, signs, embeds, and validates cryptographic content credentials, and is the reference implementation behind the Content Authenticity Initiative ecosystem. `[ai-defense]` `[global]`
- [ProofMode](https://proofmode.org/) — Mobile chain-of-custody capture with a Verify tool that detects AI-generated content in images, audio, and video, maintained by Guardian Project and WITNESS and used by journalists and humanitarian documentarians. `[ai-defense]` `[global]`

<!-- Seed entries pending maintainer review -->

## Government transparency

FOIA tooling, lobbying trackers, council-meeting transcription, public-records scrapers, budget analysis, and accountability infrastructure.

- [Aleph (OCCRP)](https://docs.aleph.occrp.org/) — open-source investigative data platform with NLP-driven entity extraction, used by journalists worldwide to surface connections across leaked documents and public records. `[uses-ai]` `[global]`
- [OpenCouncil](https://github.com/schemalabz/opencouncil) — open-source platform that transcribes, summarizes, and makes searchable municipal council meetings using AI-generated speaker recognition and subject categorization, built by the Schema Labs democracy nonprofit. `[uses-ai]` `[global]`

<!-- Seed entries pending maintainer review -->

## Journalism & source protection

Document review at scale, OSINT copilots, leak triage, source-protection tooling, and secure newsroom workflows.

- [DocumentCloud](https://www.documentcloud.org/) — secure document hosting and analysis platform with AI-assisted OCR, named-entity extraction, and AI summarization across large document sets, used by 4,000+ newsrooms to publish and investigate primary sources. `[uses-ai]` `[global]`
- [Presidio](https://github.com/microsoft/presidio) — open-source PII detection, redaction, and anonymization framework used by newsrooms to scrub leaked documents, chat logs, and transcripts before publication to protect sources. `[uses-ai]` `[global]`

<!-- Seed entries pending maintainer review -->

## Surveillance & civil-liberties defense

Anti-spyware, secure comms, facial-recognition defenses, lawful-intercept transparency, dragnet detection, and tools that surface AI-driven civil-liberties harms.

<!-- Seed entries pending maintainer review — strict AI-mode gate applies (uses-ai or ai-defense). Generic privacy tooling without AI is out of scope. -->

## Civic AI agents & scaffolds

Reusable agents, prompt libraries, recipes, and scaffolds for civic work — the "how to build" section.

<!-- Seed entries pending maintainer review -->

---

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md). Read it before opening a PR.

## License

Content is licensed under [CC BY-SA 4.0](./LICENSE). Linked projects retain their own licenses.

## Why this list exists

This repo collects AI tools that support public-interest work. The framing is deliberately neutral; the editorial filter is not. Maintainers' judgment is recorded in [`CONTEXT.md`](./CONTEXT.md) and the architectural decisions are in [`docs/adr/`](./docs/adr/).
