---
name: swot-tows
description: >
  Run a SWOT analysis that leads somewhere: evidence-backed strengths, weaknesses,
  opportunities and threats, then a TOWS matrix that turns them into strategic
  options and a prioritized recommendation. Use when the user asks for a SWOT, a
  situation analysis, or the strengths and weaknesses of a company, product, brand,
  project or career. Triggers: "SWOT", "TOWS", "strengths and weaknesses",
  "analyse SWOT", "matrice SWOT", "forces et faiblesses", "FFOM", "análisis DAFO",
  "matriz FODA", "fortalezas y debilidades", "análisis CAME".
---

# SWOT → TOWS

A SWOT is only useful if it changes a decision. This skill builds the four lists with evidence, then crosses them (TOWS) to produce strategic options.

## When to use

- A quick, overall situation analysis of a company, product, brand, project or career.
- As a synthesis after `pestel` (feeds opportunities and threats) and `vrio` (feeds strengths and weaknesses).
- Not a substitute for industry analysis: for "is this market attractive?", use `porter-five-forces`.

## Inputs

1. The subject (company, business unit, product) and the decision the analysis should inform.
2. The competitors it is compared with. Strengths and weaknesses are always relative to them.
3. Any data provided: financials, market shares, customer reviews, news.

## Method

1. **Separate internal from external.** Strengths and weaknesses are internal and controllable (resources, skills, brand, costs). Opportunities and threats are external and outside the company's control (market, regulation, technology, competitors' moves). Classic mistake: a "growing market" is an opportunity, not a strength.
2. **Make each item specific and evidenced.** Weak: "strong brand". Strong: "brand awareness of 85% in France vs 60% for the closest rival (source)". Without data, write the item as a hypothesis to check.
3. **Keep 3–5 items per quadrant**, ranked by their impact on the decision. Merge duplicates and cut anything that would be true of any company.
4. **Cross the quadrants (TOWS):**
   - **SO:** use strengths to capture opportunities.
   - **WO:** fix weaknesses in order to capture opportunities.
   - **ST:** use strengths to counter threats.
   - **WT:** reduce weaknesses and avoid threats (defensive moves).
5. **Prioritize the options** on impact, feasibility and fit with the company's resources. Recommend one or two.

## Output

```markdown
### SWOT — <subject> (vs <competitors>)
| Strengths (internal, +) | Weaknesses (internal, −) |
|---|---|
| S1 … (evidence) | W1 … (evidence) |

| Opportunities (external, +) | Threats (external, −) |
|---|---|
| O1 … (evidence) | T1 … (evidence) |

### TOWS — strategic options
| | Opportunities | Threats |
|---|---|---|
| **Strengths** | SO: … (S1 + O2) | ST: … (S2 + T1) |
| **Weaknesses** | WO: … (W1 + O1) | WT: … (W3 + T2) |

### Recommendation
<The 1–2 best options, why, and the first concrete step.>
```

## Quality bar

- No item is generic enough to describe any company.
- Each item is evidenced or explicitly marked as a hypothesis. No invented figures.
- The internal/external split is respected in every quadrant.
- Each TOWS option names the items it combines (for example S1 + O2).
- The analysis ends with a recommendation, not with the matrix.
- Written in the user's language, with the standard terms below (in Spanish, say DAFO in Spain and FODA in Latin America).

## Terminology

| English | Français | Español |
|---|---|---|
| SWOT analysis | Analyse SWOT (ou FFOM, MOFF) | Análisis DAFO (España), FODA (Latinoamérica) |
| Strengths | Forces | Fortalezas |
| Weaknesses | Faiblesses | Debilidades |
| Opportunities | Opportunités | Oportunidades |
| Threats | Menaces | Amenazas |
| TOWS matrix | Matrice TOWS (SWOT croisé) | DAFO cruzado, análisis CAME |

## Sources

- Learned, E. P., Christensen, C. R., Andrews, K. R., & Guth, W. D. (1965). *Business Policy: Text and Cases*. Irwin.
- Weihrich, H. (1982). The TOWS matrix: A tool for situational analysis. *Long Range Planning*, 15(2), 54–66.
