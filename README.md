# awesome-civic-ai

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](./LICENSE)

> A strictly-curated list of AI tools for public-interest work — election integrity, deepfake defense, government transparency, journalism, and civil-liberties defense.

If you came here looking for a tool to help your newsroom, your research, your election-monitoring team, or your civil-society organization — **start with [Contents](#contents)**. Every entry below has been vetted by humans against a strict bar. There are only a handful, on purpose.

---

## Who this list is for

> **If you're a journalist, researcher, fact-checker, election worker, or civil-society staffer**, this list is for you. Jump to [Contents](#contents), then read [How to use this list](#how-to-use-this-list).
>
> **If you're a developer or maintainer who wants to contribute a project**, read [Contributing](#contributing) first. Most pull requests are rejected — that is the point.

---

## Contents

- [Election integrity & voting](#election-integrity--voting)
- [Synthetic media & provenance](#synthetic-media--provenance)
- [Government transparency](#government-transparency)
- [Journalism & source protection](#journalism--source-protection)
- [Surveillance & civil-liberties defense](#surveillance--civil-liberties-defense)
- [Civic AI agents & scaffolds](#civic-ai-agents--scaffolds)

Generic civic-tech is out of scope — for that, see [awesome-civic-tech](https://github.com/topics/civic-tech).

---

## How to use this list

Each entry is a link to the project's home page. From there, you'll usually find documentation, a demo, and a way to reach the team — most of the projects listed actively work with newsrooms, researchers, and civil-society partners.

A few tips for non-technical readers:

- **Start with the project's own site.** The links go to the project's primary home, not its GitHub repository, so you land somewhere designed to explain what the tool does and who runs it.
- **Look for an "About," "Partners," or "Contact" page.** Most of these projects are run by nonprofits, journalism orgs, or research collectives that respond to outreach from newsrooms and civil-society groups.
- **"Actively maintained" matters.** Before adopting a tool, check that the project has commits, releases, or blog posts within the last 6–12 months. If a project has gone quiet, it may not be safe to rely on for live work.
- **You don't have to deploy it yourself.** Many listed tools offer hosted access, partner programs, or training for journalists and researchers — ask.

---

## How the tags work

Each entry carries two tags: what kind of tool it is, and where it works.

| Tag | What it means |
| --- | --- |
| `[uses-ai]` | The tool uses AI as a core capability for public-interest work. |
| `[ai-defense]` | The tool detects, defends against, or provides accountability for AI-driven harms (e.g., deepfakes, wrongful facial-recognition matches). |
| `[agent]` | A reusable agent, prompt library, or scaffold built for civic work. |
| `[global]` | Works across jurisdictions. |
| `[US]`, `[UK]`, `[BR]`, `[IN]`, ... | ISO country code — primarily applicable in one jurisdiction. |
| `[multi: US,EU]` | Applicable in multiple specific jurisdictions. |

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

- [Aleph (OCCRP)](https://aleph.occrp.org/) — open-source investigative data platform with NLP-driven entity extraction, used by journalists worldwide to surface connections across leaked documents and public records. `[uses-ai]` `[global]`
- [OpenCouncil](https://github.com/schemalabz/opencouncil) — open-source platform that transcribes, summarizes, and makes searchable municipal council meetings using AI-generated speaker recognition and subject categorization, built by the Schema Labs democracy nonprofit. `[uses-ai]` `[global]`

<!-- Seed entries pending maintainer review -->

## Journalism & source protection

Document review at scale, OSINT copilots, leak triage, source-protection tooling, and secure newsroom workflows.

- [DocumentCloud](https://www.documentcloud.org/) — secure document hosting and analysis platform with AI-assisted OCR, named-entity extraction, and AI summarization across large document sets, used by 4,000+ newsrooms to publish and investigate primary sources. `[uses-ai]` `[global]`
- [Presidio](https://github.com/microsoft/presidio) — open-source PII detection, redaction, and anonymization framework used by newsrooms to scrub leaked documents, chat logs, and transcripts before publication to protect sources. `[uses-ai]` `[global]`

<!-- Seed entries pending maintainer review -->

## Surveillance & civil-liberties defense

Anti-spyware, secure comms, facial-recognition defenses, lawful-intercept transparency, dragnet detection, and tools that surface AI-driven civil-liberties harms.

- [AI Incident Database](https://incidentdatabase.ai/) — open catalog of real-world AI harms (wrongful arrests via facial recognition, biased automated decisions, deepfake impersonation), curated by the Responsible AI Collaborative and used by researchers, regulators, and journalists to track and prevent recurrence. `[ai-defense]` `[global]`

## Civic AI agents & scaffolds

Reusable agents, prompt libraries, recipes, and scaffolds for civic work — the "how to build" section.

> **Section open for submissions.** Nothing has met the strict gate as of June 2026. Generic agent frameworks (LangGraph, CrewAI, GPT Researcher) are out of scope — this section is for civic-purpose libraries: FOIA agents, council-meeting analyzers, public-records research scaffolds, source-protection assistants. See [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## Contributing

> **We reject most pull requests. That's the point.**
>
> This list is strictly curated. The bar is high because trust in this list depends on what we keep off it as much as what we add. If your project is borderline, expect a "no" — not a slight, just the gate doing its job.

Before opening a PR, read [CONTRIBUTING.md](./CONTRIBUTING.md). It documents the gates, the categories, and the kind of evidence we look for (real users, active maintenance, public-interest fit, fit with one of the six sections above).

For the editorial reasoning behind the framing and the strict gate, see [`CONTEXT.md`](./CONTEXT.md). Architectural decisions live in [`docs/adr/`](./docs/adr/).

## License

Content is licensed under [CC BY-SA 4.0](./LICENSE). Linked projects retain their own licenses.
