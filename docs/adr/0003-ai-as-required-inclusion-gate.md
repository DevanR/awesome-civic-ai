# AI as a required inclusion gate

Every entry must demonstrably do one of three things: use AI for public-interest work, defend against AI-driven harms, or provide reusable AI agents and scaffolds for civic work. Generic civic-tech tools that don't touch AI are out of scope — not because they're unimportant, but because dozens of awesome-civic-tech lists already cover them. The AI gate is our differentiator and the reason the list exists distinct from prior art.

## Considered options

- **Civic tech broadly, AI optional** — would make us the Nth `awesome-civic-tech`. Rejected: the field is already well-served; adding another generalist list adds noise, not signal.
- **AI usage only, no AI-defense entries** — narrower and cleaner. Rejected: the AI-defense category (provenance, deepfake forensics, watermarking) is one of the most journalist-relevant areas and excluding it would amputate half the value to the journalism reader.

## Consequences

- The "AI demonstrably present" judgment is harder than it looks. A tool that uses generic OCR is borderline; a tool that uses an LLM for claim verification is clearly in. CONTRIBUTING.md needs concrete examples of borderline cases.
- Excellent civic-tech tools that don't use AI will be rejected. Reviewers should send a kind note pointing to existing awesome-civic-tech lists rather than leaving the contributor confused.
- As AI gets embedded into nearly everything, this gate will weaken over time. Revisit this ADR if "uses AI" stops being meaningfully restrictive.
