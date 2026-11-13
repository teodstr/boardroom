---
name: supply-chain-strategy
description: >
  Choose the right supply chain for a product, efficient (lean) or responsive
  (agile), using Fisher's product–supply chain match and Lee's uncertainty
  framework, then derive decisions on sourcing, inventory, production and
  distribution. Use for operations strategy, supply chain redesign, "lean vs
  agile" questions and logistics case studies. Triggers: "supply chain strategy",
  "lean vs agile", "responsive supply chain", "Fisher model", "stratégie supply
  chain", "chaîne logistique", "chaîne d'approvisionnement", "lean ou agile",
  "estrategia de cadena de suministro", "cadena de suministro ágil".
---

# Supply chain strategy

Match the supply chain to the uncertainty of the product's demand and supply, then turn that choice into concrete decisions and indicators.

## When to use

- "Should our supply chain be lean or agile?", stockouts and markdowns at the same time, rising logistics costs, supply chain case studies.
- For the business model as a whole, use `business-model-canvas`.

## Inputs

1. The product(s): demand pattern, life cycle, margins, variety, forecast accuracy.
2. The supply side: suppliers, locations, lead times, process maturity, risks.
3. Current problems and indicators: stockouts, inventory levels, costs, lead times.

## Method

1. **Characterize demand (Fisher):**
   - **Functional products:** stable, predictable demand, long life cycles, low margins, little variety (staple foods, basic clothing, consumables).
   - **Innovative products:** unpredictable demand, short life cycles, high margins, high variety (fashion, consumer electronics).
2. **Characterize supply (Lee):** stable (mature processes, reliable suppliers) or evolving (new processes, few suppliers, quality or capacity risks).
3. **Match the strategy** using the grid below.

| | Stable supply | Evolving supply |
|---|---|---|
| **Functional product** | Efficient (lean): lowest cost, high utilization, low inventory | Risk-hedging: pooled inventory, several suppliers |
| **Innovative product** | Responsive: speed, flexibility, spare capacity, build to order | Agile: responsive and risk-hedging combined |

4. **Diagnose mismatches.** An innovative product run through an efficient chain causes stockouts and markdowns. A functional product run through a responsive chain wastes money.
5. **Combine where useful:** lean upstream and agile downstream, separated by a decoupling point, with postponement (finishing the product as late as possible, once demand is known).
6. **Derive the decisions:** sourcing (one or several suppliers, nearshore or offshore), inventory (where, how much safety stock), production (make to stock, assemble to order, make to order), distribution (central or local warehouses), information sharing with partners.
7. **Pick the indicators:** cost to serve, on-time in-full (OTIF), fill rate, inventory turnover, lead time, forecast accuracy, markdowns.

## Output

```markdown
### Diagnosis — <product>
| Criterion | Observation | Reading |
|---|---|---|
| Demand predictability | … | Functional / innovative |
| Supply stability | … | Stable / evolving |

### Recommended strategy
<Efficient, risk-hedging, responsive or agile, and why.>

### Decisions
| Lever | Today | Target | Why |
|---|---|---|---|
| Sourcing | … | … | … |
| Inventory | … | … | … |
| Production | … | … | … |
| Distribution | … | … | … |

### Indicators
| Indicator | Today | Target |
|---|---|---|
```

## Quality bar

- The product is classified with evidence (demand variability, life cycle, margins), not intuition.
- Supply uncertainty is assessed separately from demand uncertainty.
- Mismatches are explained by their symptoms (stockouts, markdowns, excess cost).
- Decisions are concrete, linked to the chosen strategy, and come with indicators.
- No invented figures: label estimates as assumptions.
- Written in the user's language, with the standard terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Supply chain | Chaîne logistique (supply chain) | Cadena de suministro |
| Efficient / responsive supply chain | Supply chain efficiente / réactive | Cadena de suministro eficiente / de respuesta rápida |
| Lead time | Délai d'approvisionnement | Plazo de entrega |
| Safety stock | Stock de sécurité | Stock de seguridad |
| Postponement | Différenciation retardée | Postergación |
| Make to stock / make to order | Production sur stock / à la commande | Fabricación contra stock / bajo pedido |
| Decoupling point | Point de découplage | Punto de desacoplamiento |

## Sources

- Fisher, M. L. (1997). What is the right supply chain for your product? *Harvard Business Review*, 75(2), 105–116.
- Lee, H. L. (2002). Aligning supply chain strategies with product uncertainties. *California Management Review*, 44(3), 105–119.
- Christopher, M. (2000). The agile supply chain: Competing in volatile markets. *Industrial Marketing Management*, 29(1), 37–44.
