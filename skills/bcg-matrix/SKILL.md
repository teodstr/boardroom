---
name: bcg-matrix
description: >
  Analyze a portfolio of products, brands or business units with the BCG
  growth-share matrix (stars, cash cows, question marks, dogs) and decide where to
  invest, harvest or divest. Use for portfolio strategy, resource allocation across
  product lines, or "which products should X focus on". Triggers: "BCG matrix",
  "growth-share matrix", "portfolio analysis", "cash cow", "matrice BCG",
  "portefeuille d'activités", "vache à lait", "matriz BCG", "cartera de
  productos", "vaca lechera".
---

# BCG matrix

Place each unit of a portfolio by market growth and relative market share, then decide how to allocate cash across the portfolio.

## When to use

- A company with several products, brands or business units, and a question about where to invest.
- For new growth options (new markets, new products), use `ansoff-matrix`.

## Inputs

1. The list of units, with revenue (and margin if available).
2. For each unit: the growth rate of its market and the market shares of the unit and of its largest competitor.

## Method

1. **Define each unit's market precisely.** Results change completely with the market definition, so state it.
2. **Compute relative market share** = the unit's share ÷ the share of its largest competitor. If the unit is the leader, divide by the share of the number two (the result is above 1).
3. **Use the market's growth rate**, not the unit's own sales growth.
4. **Set the thresholds:** relative share of 1.0; market growth around 10% in the original version, or a threshold adapted to the context (economy or industry average). State the one you use.
5. **Classify each unit:**
   - **Stars** (high growth, high share): invest to keep the lead. They often use as much cash as they generate.
   - **Cash cows** (low growth, high share): harvest cash, invest only to maintain. They fund the rest.
   - **Question marks** (high growth, low share): invest heavily to gain share, or exit.
   - **Dogs** (low growth, low share): divest, harvest or reposition, unless they play a strategic role.
6. **Check the balance of the portfolio:** do cash cows fund the future? Is there a successor for each cash cow?
7. **State the limits:** share is not always profit, synergies between units are ignored, and the matrix is a snapshot. For more nuance, combine with industry attractiveness (`porter-five-forces`).

## Output

```markdown
### BCG matrix — <company>
| Unit | Market (definition) | Market growth | Relative share | Revenue | Quadrant | Action |
|---|---|---|---|---|---|---|

### Portfolio balance
<Who funds whom, gaps, succession risk.>

### Recommendations
1. …
```

## Quality bar

- Relative market share is computed against the largest competitor, not as an absolute share.
- Market growth is the market's, with a source and an explicit threshold.
- Market definitions are explicit.
- Actions differ by quadrant and take the whole portfolio into account.
- No invented market shares: if data is missing, give estimates labeled as such or ask for the data.
- Written in the user's language, with the standard terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Stars | Vedettes | Estrellas |
| Cash cows | Vaches à lait | Vacas lecheras |
| Question marks | Dilemmes | Interrogantes |
| Dogs | Poids morts | Perros |
| Relative market share | Part de marché relative | Cuota de mercado relativa |
| Business portfolio | Portefeuille d'activités | Cartera de negocios |

## Sources

- Henderson, B. D. (1970). *The Product Portfolio*. BCG Perspectives. Boston Consulting Group.
