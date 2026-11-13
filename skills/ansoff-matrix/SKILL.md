---
name: ansoff-matrix
description: >
  Map and compare growth options with the Ansoff matrix (market penetration, market
  development, product development, diversification), weighing the risk of each
  and the best way to grow (organic, partnership, acquisition). Use for growth
  strategy, "how can X grow", new market or new product decisions. Triggers:
  "Ansoff", "growth strategy", "growth options", "diversification", "matrice
  d'Ansoff", "stratégie de croissance", "axes de développement", "matriz de
  Ansoff", "estrategia de crecimiento".
---

# Ansoff matrix

Lay out the concrete ways a company can grow, compare their risk and return, and recommend where to go first.

## When to use

- "How can X grow?", "Should we launch a new product or go abroad?", growth plans in business plans.
- To decide between existing units rather than new growth options, use `bcg-matrix`.

## Inputs

1. The company's current products and markets (a market is a customer segment, a geography or both).
2. Its growth goal (revenue, horizon) and its constraints (budget, skills, risk appetite).

## Method

1. **Describe the starting point:** current products, current markets, where the revenue comes from today.
2. **Generate 1–3 concrete options per quadrant:**
   - **Market penetration** (existing products, existing markets): win share, increase usage, adjust pricing, build loyalty.
   - **Market development** (existing products, new markets): new countries, new segments, new channels.
   - **Product development** (new products, existing markets): extensions, new features, related services.
   - **Diversification** (new products, new markets): related (shares skills or assets) or unrelated. The riskiest quadrant.
3. **Evaluate each option** from 1 to 5 on market attractiveness (size, growth, margin), fit with the company's capabilities (see `vrio`), risk and investment needed. Note how long each option takes to pay off.
4. **Choose the mode of growth** for the best options: organic, partnership or joint venture, acquisition, franchising or licensing.
5. **Recommend a sequence**, usually starting with the option that has the best mix of fit and risk.

## Output

```markdown
### Growth options — <company>
| | Existing products | New products |
|---|---|---|
| **Existing markets** | Penetration: … | Product development: … |
| **New markets** | Market development: … | Diversification: … |

### Evaluation (1 = poor, 5 = excellent)
| Option | Attractiveness | Fit | Low risk | Low investment | Total | Mode |
|---|---|---|---|---|---|---|

### Recommendation
<Which option first, by which mode, with the first milestone.>
```

## Quality bar

- Options are concrete ("sell the range in Spain through El Corte Inglés"), not quadrant names.
- Risk rises from penetration to diversification: explain it for each option.
- The company's capabilities filter the options.
- The analysis ends with a recommendation and a mode of growth.
- Written in the user's language, with the standard terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Market penetration | Pénétration de marché | Penetración de mercado |
| Market development | Développement de marché | Desarrollo de mercado |
| Product development | Développement de produit | Desarrollo de producto |
| Related / unrelated diversification | Diversification liée (concentrique) / conglomérale | Diversificación relacionada / no relacionada |
| Organic / external growth | Croissance interne / externe | Crecimiento orgánico / externo |

## Sources

- Ansoff, H. I. (1957). Strategies for diversification. *Harvard Business Review*, 35(5), 113–124.
