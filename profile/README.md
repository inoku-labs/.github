# Inoku Labs

**Proof, not promises.** Inoku is an independent research lab working on one question: how do we make AI agents tell the truth about their own work?

When an AI agent says "done", it should be true. Today it often isn't. In one 2026 study, false success (an agent reporting a task complete when it wasn't) made up 75.8% of failures among coding agents that reported their own status ([Advani, 2026](https://arxiv.org/abs/2606.09863)). The usual check, an LLM judge reading the agent's transcript, caught it at an AUROC of no better than 0.65. Inoku builds ways to measure that gap and close it.

## What we're building

| Repository | What it is | Status |
| --- | --- | --- |
| [inoku-verified](https://github.com/inoku-labs/inoku-verified) | An independent evaluation of how often an agent's "done" is true, and how often its "I couldn't" is true, on a private test suite. The method, benchmark and the rules of the Inoku Verified™ mark will be published here. | In development |
| [inoku-os](https://github.com/inoku-labs/inoku-os) | The Linux distribution the evaluation tools ship in. | In development |

Nothing here is for sale. Research, education and open-source projects will use everything at no cost, and so will organisations under 10 people and $1M in revenue; see [pricing](https://inoku.com/pricing/).

## Get involved

- **Private beta.** Run the first builds of the tools on your own agent and tasks, free, with invites in waves: [inoku.com/beta](https://inoku.com/beta/)
- **Design partners.** Five teams whose agents we evaluate ourselves during the programme: [inoku.com/design-partners](https://inoku.com/design-partners/)
- **Research notes.** Evidence-first guides and notes on false success, agent verification, benchmarks, RL for agents, sandboxing and compliance: [inoku.com/blog](https://inoku.com/blog/)

## Principles

1. **Evidence over assertion.** Every factual claim we publish links to its source.
2. **Honest failure is a feature.** An agent that says "I couldn't" when that's true is worth more than one that always says "done".
3. **Open by default.** The method, the tools and the benchmark go public together, under an open licence, once the method is ready to be checked.
4. **Independent.** Payment never changes a score.

Inoku is based in Larnaka, Cyprus, founded in 2026 by [Ivan Popov](https://inoku.com/author/ivan-popov/). Contact: [hello@inoku.com](mailto:hello@inoku.com) · [inoku.com](https://inoku.com/) · [LinkedIn](https://www.linkedin.com/company/inoku-labs/)
