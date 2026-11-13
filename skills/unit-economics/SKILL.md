---
name: unit-economics
description: >
  Check whether a business makes money on each customer or unit: contribution
  margin, customer acquisition cost (CAC), lifetime value (LTV), LTV/CAC, payback
  period and break-even point, with every formula shown. Use for startups, pricing,
  marketing budgets, subscription or e-commerce models and business plans.
  Triggers: "unit economics", "CAC", "LTV", "CLV", "payback", "break-even",
  "contribution margin", "économie unitaire", "coût d'acquisition client",
  "valeur vie client", "seuil de rentabilité", "point mort", "punto de equilibrio",
  "coste de adquisición de clientes", "valor de vida del cliente".
---

# Unit economics

Find out whether each sale or each customer creates value, how long it takes to recover acquisition costs, and which lever matters most.

## When to use

- "Is this business model profitable?", "How much can we spend to acquire a customer?", "When do we break even?"
- To describe the whole business model first, use `business-model-canvas`.

## Inputs

1. The unit: one order, one customer, one month of subscription, one store.
2. Price, variable costs, marketing spend, new customers, retention or churn, fixed costs. Use the user's figures first.

## Method

1. **Contribution margin per unit** = price − variable costs (cost of goods, payment fees, shipping, commissions). Also give it as a percentage of the price.
2. **Customer acquisition cost (CAC)** = sales and marketing spend over a period ÷ new customers won in that period. Distinguish blended CAC (all customers) from paid CAC (customers from paid channels).
3. **Lifetime value (LTV), gross-margin based:**
   - Subscription: monthly revenue per customer × gross margin % ÷ monthly churn rate.
   - Repeat purchases: contribution per order × orders per year × expected years as a customer.
4. **LTV/CAC.** A common rule of thumb for subscription businesses is at least 3. It is a benchmark, not a law.
5. **CAC payback (months)** = CAC ÷ (monthly revenue per customer × gross margin %). Under 12 months is a common benchmark in software subscriptions.
6. **Break-even:** units needed = fixed costs ÷ contribution margin per unit; break-even revenue = fixed costs ÷ contribution margin %.
7. **Sensitivity:** test price, churn, CAC and margin. Say which lever moves the result most, and give the 2–3 actions with the biggest effect.

## Output

```markdown
### Inputs
| Input | Value | Source or assumption |
|---|---|---|

### Calculations
<Each formula with the numbers in it.>

### Results
| Metric | Value | Benchmark | Verdict |
|---|---|---|---|
| Contribution margin | … | | |
| CAC | … | | |
| LTV | … | | |
| LTV/CAC | … | ≥ 3 | |
| CAC payback | … | < 12 months | |
| Break-even | … | | |

### Sensitivity
| Lever | −20% | Base | +20% |
|---|---|---|---|

### Recommendations
1. …
```

## Quality bar

- Every formula is shown with its numbers, so the user can check it.
- Currency and period are consistent everywhere (monthly vs yearly, before or after tax).
- LTV is based on margin, never on revenue alone.
- Missing data is requested or replaced by labeled assumptions. No invented benchmarks: present rules of thumb as rules of thumb.
- The analysis ends with the levers to pull.
- Written in the user's language, with the standard terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Unit economics | Économie unitaire | Economía unitaria |
| Contribution margin | Marge sur coûts variables | Margen de contribución |
| Customer acquisition cost (CAC) | Coût d'acquisition client (CAC) | Coste de adquisición de clientes (CAC) |
| Customer lifetime value (LTV, CLV) | Valeur vie client (CLV) | Valor del ciclo de vida del cliente (CLV) |
| Churn rate | Taux d'attrition (churn) | Tasa de abandono (churn) |
| Break-even point | Seuil de rentabilité (point mort) | Punto de equilibrio |
| Fixed / variable costs | Charges fixes / variables | Costes fijos / variables |

## Sources

- Gupta, S., & Lehmann, D. R. (2005). *Managing Customers as Investments*. Wharton School Publishing.
- Skok, D. (n.d.). *SaaS Metrics 2.0: A Guide to Measuring and Improving What Matters*. For Entrepreneurs. https://www.forentrepreneurs.com/saas-metrics-2/
