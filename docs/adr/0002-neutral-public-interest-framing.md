# Neutral public-interest framing despite a democracy-focused motivator

The repo's motivating crisis is democratic backsliding and the misinformation environment — that's the reason it exists. But the repo presents itself publicly as "AI tools for public-interest work," with no overt political framing in the README. The split is deliberate. Neutral framing travels further institutionally, broadens the contributor pool, and makes the list harder to dismiss as partisan. The motivator stays in maintainer judgment — it filters what gets merged — without becoming the marketing.

## Considered options

- **Explicitly pro-democracy, anti-authoritarian framing** — most honest about the motivator. Rejected: signals partisan to readers outside the immediate political tradition, narrows the contributor base, and makes the list easy to caricature in adversarial contexts. The cost outweighs the integrity gain.
- **Pro-democracy but adversary-agnostic** — names democracy as the value without naming specific regimes/movements. Rejected as too close to neutral framing in practice but with extra surface area for "why did you single out X?" criticism.

## Consequences

- Maintainers must hold the motivator privately and use it as the filter when judging PRs. If maintainers forget the motivator, the list drifts into "every civic-tech AI tool" — including ones the motivator would reject (police records vendors, AI-for-government surveillance marketed as public-interest).
- The CONTEXT.md flagged ambiguity captures this tension explicitly so future maintainers don't lose the through-line.
- If the framing ever needs to become explicit — e.g., a regime targets civic-tech maintainers and neutrality stops being protective — this ADR should be superseded, not silently abandoned.
