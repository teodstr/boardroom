---
name: business-analysis
description: >
  Structure any business question or case study like a strategy consultant: frame
  the decision, pick the right frameworks, back every point with evidence and end
  with a clear recommendation. Use this skill whenever a company, a founder or a
  student must choose between strategic options (open a new location, enter a
  city or a country, launch a product or a channel first, grow or cut), even when
  the question is short, as well as for case studies, "analyze this company" and
  business-school assignments. Triggers: "case study", "business case", "analyze
  this company", "what should X do", "should we open", "expand to", "étude de cas",
  "analyse stratégique", "faut-il ouvrir", "s'implanter", "recommandation
  stratégique", "caso práctico", "análisis estratégico", "qué debería hacer",
  "deberíamos abrir".
---

# Business analysis

Turn an open business question into a structured, evidence-backed recommendation. This skill frames the problem and chooses the frameworks; the other skills in this pack do the detailed work.

## When to use

- Open questions: "Should a French bakery chain enter the UK?", "Why is this brand losing market share?", "Analyse ce cas".
- A case study, annual report or company description to analyze.
- Not for a single named framework ("do a SWOT"): use that framework's skill directly.

## Inputs

1. The decision to make and who makes it (CEO, investor, marketing team, a jury).
2. The company, its industry and its geography.
3. The material provided (case text, figures, links). Treat it as the primary source.

If the question is too vague, ask at most two clarifying questions. If the user wants you to proceed anyway, list your assumptions in a few lines and go.

## Method

1. **Frame the decision.** Rewrite the question as one decision with a scope and a horizon: "Should X do Y in market Z within N years?" State it in four lines with SCQA: Situation, Complication, Question, Answer (your starting hypothesis).
2. **Build an issue tree.** Split the question into 2–4 sub-questions that are mutually exclusive and collectively exhaustive (MECE). For example: Is the market attractive? Can we win? Is it worth it financially? Can we execute?
3. **Pick 2–4 frameworks** with the routing table below. More frameworks dilute the answer.
4. **Run each framework** with its skill and keep only the findings that change the answer.
5. **Lead with the answer** (Pyramid Principle): the recommendation first, then the three strongest arguments, then the risks and how to mitigate them.
6. **Make it actionable:** next steps with an owner, a date and a success indicator.

### Routing table

| Sub-question | Skill |
|---|---|
| What is changing in the macro environment? | `pestel` |
| Is the industry attractive? Who captures the profits? | `porter-five-forces` |
| What are the company's real advantages? | `vrio`, `swot-tows` |
| How does the company make money? | `business-model-canvas` |
| Where should it grow? | `ansoff-matrix`, `bcg-matrix` |
| How can it escape head-to-head competition? | `blue-ocean` |
| How big is the opportunity? | `market-sizing` |
| Does it make money on each customer? | `unit-economics` |
| Who should it target, and how can it stand out? | `stp-positioning`, `marketing-mix` |
| How should it source, make and deliver? | `supply-chain-strategy` |
| Something went wrong publicly | `crisis-communication` |
| Luxury or premium brand | `luxury-brand-strategy` |

## Output

```markdown
## Recommendation
<One sentence: what to do, how, by when.>

## Why
1. <Argument + evidence>
2. <Argument + evidence>
3. <Argument + evidence>

## Analysis
<One short section per framework, each ending with "So what: …">

## Risks and mitigations
| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|

## Next steps
| Action | Owner | When | Success indicator |
|---|---|---|---|

## Assumptions and sources
```

## Quality bar

- The recommendation is a decision ("Enter Spain in 2027 through franchising"), not a summary ("Spain has potential").
- Every claim rests on the user's material, a cited source or an explicitly labeled assumption. Never invent figures: give a reasoned estimate, or say which data would settle the point.
- Each framework section ends with its consequence for the decision. Findings that change nothing are cut.
- Written in the user's language, with the standard terms from each skill's terminology table.

## Terminology

| English | Français | Español |
|---|---|---|
| Case study | Étude de cas | Caso práctico |
| Issue tree | Arbre des problèmes | Árbol de problemas |
| Key success factors | Facteurs clés de succès (FCS) | Factores clave de éxito |
| Recommendation | Recommandation | Recomendación |
| Pyramid Principle | Principe de la pyramide (Minto) | Principio de la pirámide (Minto) |

## Sources

- Minto, B. (1996). *The Minto Pyramid Principle: Logic in Writing, Thinking and Problem Solving*. Minto International.
- Rasiel, E. M. (1999). *The McKinsey Way*. McGraw-Hill.
