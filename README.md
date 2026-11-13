<div align="center">

# boardroom

**Business-school frameworks, as skills for your AI agent.**

SWOT · Porter's Five Forces · BCG · Ansoff · Blue Ocean · Business Model Canvas · TAM/SAM/SOM · Unit economics · and more

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-16-black.svg)](#the-skills)
[![Languages](https://img.shields.io/badge/languages-EN%20%7C%20FR%20%7C%20ES-green.svg)](#works-in-english-french-and-spanish)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**English** · [Français](README.fr.md) · [Español](README.es.md)

</div>

---

Ask an AI agent for a SWOT and you usually get four generic lists that would fit any company. Ask it to size a market and you get a confident number from nowhere.

**boardroom** gives your agent the method a demanding strategy professor would expect: a precise scope, evidence for every claim, labeled assumptions instead of invented numbers, a "so what" for every finding, and a clear recommendation at the end.

## Install

**Most coding agents** (Claude Code, Codex, Cursor, Windsurf, Cline and more):

```bash
npx skills add teodstr/boardroom -g
```

**Claude Code**, as a plugin:

```
/plugin marketplace add teodstr/boardroom
/plugin install boardroom@boardroom
```

**Manually:** copy the folders in [`skills/`](skills) into your agent's skills directory.

## Use it

Just ask. The right skill loads on its own.

```
We run 12 bakeries in Bordeaux. Should we open in Toulouse or launch delivery first?
Fais-moi une analyse PESTEL du marché du vin bio en Allemagne.
Haz un DAFO de Zara frente a Shein y propón una estrategia.
What are the unit economics of a meal-kit subscription at €60 a box?
```

## The skills

| Skill | Framework | Use it for |
|---|---|---|
| [`business-analysis`](skills/business-analysis/SKILL.md) | Issue tree, SCQA, Pyramid Principle | Case studies and open strategy questions: picks the frameworks, ends with a recommendation |
| [`swot-tows`](skills/swot-tows/SKILL.md) | SWOT + TOWS matrix | A situation analysis that turns into strategic options |
| [`pestel`](skills/pestel/SKILL.md) | PESTEL | The macro environment of a market or a country |
| [`porter-five-forces`](skills/porter-five-forces/SKILL.md) | Five Forces | Industry attractiveness and competition |
| [`vrio`](skills/vrio/SKILL.md) | VRIO | Sustainable competitive advantage |
| [`ansoff-matrix`](skills/ansoff-matrix/SKILL.md) | Ansoff matrix | Growth options and their risk |
| [`bcg-matrix`](skills/bcg-matrix/SKILL.md) | BCG growth-share matrix | A portfolio of products or business units |
| [`business-model-canvas`](skills/business-model-canvas/SKILL.md) | Business Model Canvas, Value Proposition Canvas | How a business creates and captures value |
| [`blue-ocean`](skills/blue-ocean/SKILL.md) | Strategy canvas, ERRC grid | Escaping head-to-head competition |
| [`market-sizing`](skills/market-sizing/SKILL.md) | TAM / SAM / SOM | Market size, top-down and bottom-up |
| [`unit-economics`](skills/unit-economics/SKILL.md) | CAC, LTV, payback, break-even | Profitability per customer or per unit |
| [`stp-positioning`](skills/stp-positioning/SKILL.md) | Segmentation, targeting, positioning | Choosing a target and a position |
| [`marketing-mix`](skills/marketing-mix/SKILL.md) | 4P / 7P | Coherent marketing and launch plans |
| [`supply-chain-strategy`](skills/supply-chain-strategy/SKILL.md) | Fisher model, Lee's uncertainty framework | Lean or agile supply chain |
| [`crisis-communication`](skills/crisis-communication/SKILL.md) | SCCT | Crisis response, statements, stakeholder plan |
| [`luxury-brand-strategy`](skills/luxury-brand-strategy/SKILL.md) | Kapferer's identity prism, rules of luxury | Luxury and premium brands |

## What every skill enforces

- **A precise scope.** "Premium electric cars in Europe", not "cars".
- **Evidence or a label.** Every claim comes from your material, a source, or a clearly marked assumption. No invented statistics.
- **So what?** Each finding states what it changes for the decision.
- **A recommendation.** Analyses end with a decision and next steps, not with a matrix.
- **Real sources.** Each skill cites the original authors (Porter, Barney, Kim & Mauborgne, Osterwalder…).

## Works in English, French and Spanish

Ask in any of the three languages and the agent answers with the terms business schools actually use: *analyse SWOT* in French, *DAFO* in Spain and *FODA* in Latin America, *les 5 forces de Porter*, *las cinco fuerzas de Porter*, *vaches à lait*, *vacas lecheras*… Every skill ends with a terminology table, and adding a language is one of the easiest ways to contribute.

## Contributing

boardroom is built to be easy to contribute to, even if you have never written code: a skill is a single Markdown file.

- **Add a framework** from the [roadmap](ROADMAP.md): McKinsey 7S, value chain, Balanced Scorecard, Lean Canvas, Hofstede, Kotter…
- **Add a language** to the terminology tables (German, Italian, Portuguese…) or translate this README.
- **Improve a skill** with a clearer step, a common mistake to avoid, or a better source.
- **Report a weak output:** open an issue with your prompt and what the agent produced.

Start with [CONTRIBUTING.md](CONTRIBUTING.md). Every pull request is checked automatically.

## License

[MIT](LICENSE). Maintained by [teodstr](https://github.com/teodstr), business-school student. Built with the help of Claude.
