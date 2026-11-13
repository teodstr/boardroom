---
name: market-sizing
description: >
  Estimate the size of a market (TAM, SAM, SOM) with transparent top-down and
  bottom-up calculations, explicit assumptions, scenarios and a sanity check. Use
  for business plans, pitch decks, market entry, "how big is the market for X",
  or case-interview estimates. Triggers: "market size", "TAM SAM SOM", "market
  sizing", "how big is the market", "taille de marché", "marché potentiel",
  "estimer le marché", "tamaño de mercado", "mercado potencial",
  "dimensionar el mercado".
---

# Market sizing

Estimate how big an opportunity is, in a way anyone can check: every number has a source or a stated assumption, and every step of the calculation is visible.

## When to use

- Business plans, pitch decks, market entry decisions, investment memos.
- Case-interview estimates ("How many coffees are sold in Paris each day?").
- For the profitability of each customer, use `unit-economics`.

## Inputs

1. The product, the customer, the geography and the unit (value per year in a currency, or volume).
2. Any data the user has: industry reports, statistics, prices, customer counts.

## Method

1. **Define the market precisely:** what is sold, to whom, where, over what period. Most errors come from a vague definition.
2. **Define the three levels:**
   - **TAM** (total addressable market): total demand for the category in the geography, at 100% market share.
   - **SAM** (serviceable available market): the part the company can actually serve with its offer, channels and geography.
   - **SOM** (serviceable obtainable market): the share it can realistically win in 3–5 years, given competition and resources.
3. **Top-down:** start from a published total (with its source) and apply successive filters, each one sourced or labeled as an assumption.
4. **Bottom-up:** number of target customers × adoption rate × purchases per year × average price. Prefer it for the SOM: it is what investors trust.
5. **Triangulate:** compare both results. If they differ by more than about 2×, revisit the assumptions.
6. **Run scenarios:** low, base and high on the two most uncertain assumptions.
7. **Round the results.** False precision ruins credibility.

For case interviews without data: break the population into segments, use round numbers, say each assumption aloud, and check the result against common sense.

## Output

```markdown
### Market definition
<Product, customer, geography, unit, period.>

### Top-down
| Step | Value | Source or assumption |
|---|---|---|

### Bottom-up
| Driver | Value | Source or assumption |
|---|---|---|
Customers × adoption × frequency × price = …

### Results
| Level | Value | How |
|---|---|---|
| TAM | … | … |
| SAM | … | … |
| SOM | … | … |

### Scenarios
| Scenario | Key assumptions | SOM |
|---|---|---|

### So what
<What the size means for the decision.>
```

## Quality bar

- Every input is labeled **Source** (with a reference) or **Assumption** (with its reasoning). No figure is presented as a fact without a source.
- Units and periods are consistent at every step, and the formulas are visible.
- Top-down and bottom-up are both done and compared.
- The SOM is realistic compared with the shares that competitors hold.
- Results are rounded and end with what they mean for the decision.
- Written in the user's language, with the standard terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Total addressable market (TAM) | Marché total adressable | Mercado total direccionable |
| Serviceable available market (SAM) | Marché adressable accessible | Mercado disponible |
| Serviceable obtainable market (SOM) | Part de marché atteignable | Mercado obtenible |
| Top-down / bottom-up | Approche descendante / ascendante | Enfoque descendente / ascendente |
| Assumption | Hypothèse | Supuesto |

## Sources

- Blank, S., & Dorf, B. (2012). *The Startup Owner's Manual*. K&S Ranch.
