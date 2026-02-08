# Contributing to the Botcoin White Paper

This paper is open source under CC BY 4.0. Contributions that improve the rigor, accuracy, or clarity of the work are welcome.

## What We're Looking For

- **Data corrections** — If production data has changed or a cited source has been updated, submit a PR with the correction and evidence.
- **Formula improvements** — Alternative valuation approaches, better gas calibration models, or improved sybil analysis with supporting math.
- **New sections** — Formal game-theoretic analysis, mechanism design proofs, empirical token velocity modeling.
- **Citation additions** — Relevant academic work in agent economics, proof-of-useful-work systems, or LLM cost modeling.
- **Clarity edits** — Tighter writing, better explanations, fixed ambiguities.

## What We're Not Looking For

- Marketing language or hype
- Speculative price predictions
- Comparisons to unrelated projects without analytical substance
- Changes that remove honest limitations or caveats

## How to Submit

1. Fork the repository
2. Create a branch: `git checkout -b improvement/your-topic`
3. Make your changes to `paper.md`
4. If adding data, place CSVs in `data/` and reference them
5. Submit a pull request with a clear description of what changed and why

## Style Guide

- Academic tone, not marketing tone
- All claims must be verifiable or clearly marked as projections
- Cite sources using numbered references `[N]`
- Use standard markdown (renders natively on GitHub)
- Keep equations in code blocks for readability
