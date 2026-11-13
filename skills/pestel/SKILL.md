---
name: pestel
description: >
  Scan the macro environment of a market with PESTEL (Political, Economic, Social,
  Technological, Environmental, Legal) and keep only the trends that matter, rated
  by impact and likelihood. Use for market entry, country analysis, industry
  outlook, or the external half of a SWOT. Triggers: "PESTEL", "PESTLE", "PEST",
  "macro environment", "external analysis", "analyse PESTEL", "macro-environnement",
  "environnement externe", "análisis PESTEL", "macroentorno", "entorno general".
---

# PESTEL

Identify the external forces that will shape a market over the next 3–5 years, and say which ones matter for the decision at hand.

## When to use

- Entering a new country or market, assessing an industry's outlook, preparing the opportunities and threats of a SWOT.
- Not for competition: competitors, suppliers and buyers belong in `porter-five-forces`.

## Inputs

1. The market (industry + geography) and the time horizon.
2. The company or project, if there is one: impact is assessed for it.
3. Sources provided by the user. Otherwise use well-established facts, and flag anything that may have changed recently so the user can check it.

## Method

1. **List the factors that actually affect this market**, dimension by dimension:
   - **Political:** government stability, trade policy and tariffs, subsidies, public procurement.
   - **Economic:** growth, inflation, interest and exchange rates, purchasing power, unemployment.
   - **Social:** demographics, lifestyles, values, education, health, consumption habits.
   - **Technological:** innovation, digital adoption, automation, research intensity, infrastructure.
   - **Environmental:** climate risks, resource scarcity, carbon rules, consumers' environmental expectations.
   - **Legal:** labour law, consumer protection, competition law, data protection, product standards.
2. **Write each factor as a trend with a direction** ("carbon pricing rising and covering more sectors"), not as a topic ("environment").
3. **Rate each factor:** impact on the company (high/medium/low, positive or negative) and likelihood or timing.
4. **Keep the 5–8 factors that matter most.** A law is Legal; the political will behind it is Political. Don't count the same fact twice.
5. **Turn them into opportunities and threats**, and state the consequence for the decision.

## Output

```markdown
### PESTEL — <market>, <horizon>
| Dimension | Trend (direction) | Evidence / source | Impact on <company> | Likelihood | O/T |
|---|---|---|---|---|---|
| Political | … | … | High, negative | High | T |

### Key takeaways
1. <Most important trend> → <consequence for the decision>
2. …
3. …
```

## Quality bar

- Factors are specific to this market and geography ("digitalization" alone is not a factor).
- Each factor has a direction, an impact rating, and a source or a "to verify" flag. No invented statistics.
- A short ranked list beats an exhaustive one.
- The output ends with consequences for the decision, not with the table.
- Written in the user's language, with the standard terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| PESTEL analysis | Analyse PESTEL | Análisis PESTEL |
| Macro environment | Macro-environnement | Macroentorno |
| Political / Economic / Social | Politique / Économique / Socioculturel | Político / Económico / Sociocultural |
| Technological / Environmental / Legal | Technologique / Écologique / Légal | Tecnológico / Ecológico / Legal |
| Weak signal | Signal faible | Señal débil |

## Sources

- Aguilar, F. J. (1967). *Scanning the Business Environment*. Macmillan.
- Johnson, G., Scholes, K., & Whittington, R. (2008). *Exploring Corporate Strategy* (8th ed.). FT Prentice Hall.
