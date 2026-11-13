---
name: <skill-name, in kebab-case and identical to the folder name, for example mckinsey-7s>
description: >
  <What the skill does, in one or two sentences that start with a verb.>
  Use when <the situations, questions and assignments that should load this skill,
  in plain words>. Triggers: "<English keyword, as users type it>", "<another English
  keyword, …>", "<mot-clé en français, …>", "<autre mot-clé, …>", "<palabra clave en
  español, …>", "<otra palabra clave, …>".
---

<!--
How to use this template:
1. Copy this file to skills/<skill-name>/SKILL.md (the file must be named exactly SKILL.md).
2. Replace every <...> with your own words, then delete this comment.
3. Keep the section titles and their order: the automatic check looks for them.
4. Aim for 80 to 150 lines. Put long material in skills/<skill-name>/references/.
5. Run python3 scripts/validate_skills.py before you open a pull request.
-->

# <Framework name, as people usually write it>

<One or two sentences: the decision this framework helps with, and what the skill adds. The agent already knows the definition, so tell it how to do the analysis well.>

## When to use

- <A situation or a question where this framework is the right tool, in the words a user would use.>
- <How it fits with the other skills, for example "after `pestel`, to feed the opportunities of `swot-tows`".>
- Not for <a related question it cannot answer, for example "is this industry attractive?">: use `<other-skill, for example porter-five-forces>` instead.

## Inputs

1. The subject (company, product, market or project) and the decision the analysis should inform.
2. <The scope the framework needs, for example the geography, the time horizon or the competitors.>
3. Any data the user provides. Ask for what is missing instead of guessing.

## Method

1. **<First step, for example "Set the scope".>** <What to do, how to do it well, and the classic mistake to avoid.>
2. **<Second step, same format.>** <…>
3. **<Third step, same format.>** <…>
4. **Draw the implications.** <What the results mean for the decision, in two or three sentences.>

Every step relies on the user's material or a cited source. When data is missing, state a clearly labeled assumption. Never invent figures.

## Output

```markdown
### <Framework>: <subject>
<A table or a short structure that the agent fills in.>

### Recommendation
<The decision, why, and the first concrete step.>
```

## Quality bar

- <A check specific to this framework, for example "each element is assessed with evidence".>
- Every claim is backed by evidence or explicitly marked as an assumption. No invented figures.
- The analysis ends with a recommendation, not with the framework.
- Written in the user's language, with the standard terms below.

## Terminology

| English | Français | Español |
|---|---|---|
| <term, as used in English> | <terme, tel qu'on l'emploie en français> | <término, tal como se usa en español> |

## Sources

- <Author, A. (Year). Title of the article. *Journal*, volume(issue), pages.>
- <Author, A. (Year). *Title of the book*. Publisher.>
