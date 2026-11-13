---
name: porter-five-forces
description: >
  Assess how attractive an industry is and who captures its profits with Porter's
  Five Forces (rivalry, threat of new entrants, threat of substitutes, buyer power,
  supplier power). Use for industry attractiveness, market entry, competitive
  analysis, or explaining why an industry is more or less profitable. Triggers:
  "five forces", "Porter", "industry analysis", "competitive landscape",
  "5 forces de Porter", "analyse sectorielle", "intensité concurrentielle",
  "cinco fuerzas de Porter", "análisis sectorial", "análisis del sector".
---

# Porter's Five Forces

Explain an industry's profitability by the structure of its competition, then work out where a company can position itself.

## When to use

- "Is this industry attractive?", "Should we enter this market?", "Why are margins so low in X?"
- Not for macro trends (use `pestel`) or a single company's capabilities (use `vrio`).

## Inputs

1. A precisely defined industry: product scope and geography ("premium electric cars in Europe", not "cars"). Most mistakes come from a badly defined industry.
2. The company's position in it, if relevant.
3. Any data: market shares, margins, number of players, switching costs.

## Method

For each force, rate the intensity (high/medium/low) and give its **drivers** and **evidence**:

1. **Rivalry among existing competitors:** number and size of players, industry growth, fixed costs, differentiation, exit barriers.
2. **Threat of new entrants:** economies of scale, capital needed, brand loyalty, access to distribution, regulation, how hard incumbents would fight back.
3. **Threat of substitutes:** other ways to meet the same need (train vs plane), their price-performance, the cost of switching.
4. **Bargaining power of buyers:** concentration, volumes, switching costs, price sensitivity, ability to integrate backward.
5. **Bargaining power of suppliers:** concentration, uniqueness of inputs, switching costs, ability to integrate forward.

Then:

6. **Conclude on attractiveness.** Strong forces mean lower average profitability. Say which force matters most.
7. **Look at the dynamics:** how each force is likely to change over 3–5 years.
8. **Deduce the strategy:** where to position to be shielded from the strongest forces, or how to reshape them.

Government, technology and complementary products are not forces: treat them as factors that act on the five forces.

## Output

```markdown
### Five Forces — <industry, geography>
| Force | Intensity | Key drivers | Evidence | Trend |
|---|---|---|---|---|
| Rivalry | High | … | … | ↑ |
| New entrants | … | … | … | … |
| Substitutes | … | … | … | … |
| Buyer power | … | … | … | … |
| Supplier power | … | … | … | … |

### Overall attractiveness
<High / medium / low, and the force that drives it.>

### Implications for <company>
1. …
```

## Quality bar

- The industry is narrow enough to have a single competitive structure.
- Every intensity rating is justified by drivers and evidence. No invented market shares or margins.
- Buyers and suppliers are the industry's direct customers and suppliers (not end consumers by default).
- The analysis ends with where the profits are made and what the company should do.
- Written in the user's language, with the standard terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| Five Forces | Les 5 forces de Porter | Las cinco fuerzas de Porter |
| Rivalry among competitors | Intensité concurrentielle | Rivalidad entre competidores |
| Threat of new entrants | Menace des nouveaux entrants | Amenaza de nuevos competidores |
| Threat of substitutes | Menace des produits de substitution | Amenaza de productos sustitutivos |
| Bargaining power of buyers / suppliers | Pouvoir de négociation des clients / des fournisseurs | Poder de negociación de los clientes / de los proveedores |
| Barriers to entry | Barrières à l'entrée | Barreras de entrada |

## Sources

- Porter, M. E. (1979). How competitive forces shape strategy. *Harvard Business Review*, 57(2), 137–145.
- Porter, M. E. (2008). The five competitive forces that shape strategy. *Harvard Business Review*, 86(1), 78–93.
