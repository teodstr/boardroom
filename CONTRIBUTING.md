# Contributing to boardroom

Thanks for helping! You don't need to be a developer: a skill is one Markdown file, and you can do everything from the GitHub website.

## Ways to contribute

| Contribution | Time | How |
|---|---|---|
| Add a language | 15 min | Add a column (Deutsch, Italiano, Português…) to the Terminology table of one or more skills |
| Translate the README | 30 min | Copy `README.md` to `README.<language code>.md` and translate it |
| Add a framework | 1–2 h | Pick one in [ROADMAP.md](ROADMAP.md) and follow the steps below |
| Improve a skill | 30 min | A clearer step, a common mistake to avoid, a better source |
| Add a worked example | 1 h | Add `examples/<skill>-<case>.md` with a full analysis of a real, public case |
| Report a weak output | 5 min | Open an issue with your prompt, your agent and what went wrong |

## Add a new skill

1. Check [ROADMAP.md](ROADMAP.md) and the open issues, then comment on the issue to say you're working on it.
2. Create `skills/<skill-name>/SKILL.md`, in kebab-case (for example `skills/mckinsey-7s/SKILL.md`). Start from [templates/SKILL.template.md](templates/SKILL.template.md).
3. Fill in every section: When to use, Inputs, Method, Output, Quality bar, Terminology, Sources.
4. Add the skill to the table in `README.md` (and in `README.fr.md` and `README.es.md` if you can).
5. Run the checks with `python3 scripts/validate_skills.py`, or let the automatic check run on your pull request.
6. Open a pull request.

## What makes a good skill

- **It teaches a method, not a definition.** The agent already knows what a SWOT is. The skill tells it how to do one well.
- **It forbids invented numbers.** It asks for evidence or clearly labeled assumptions.
- **It ends with a decision.** The output template finishes with implications or a recommendation.
- **It is short.** Aim for 80 to 150 lines. Put long material in `skills/<name>/references/`.
- **It cites real sources.** Original authors and works, with full references anyone can check.
- **It is written in your own words.** Don't copy text from books, courses or websites: paraphrase and cite.
- **Its description triggers it.** Say what the skill does, when to use it, and include keywords in English, French and Spanish.

## Pull requests

- One skill or one topic per pull request.
- Describe what you changed and why.
- The maintainer reviews every pull request. Small, focused ones get merged fastest.
- If you used an AI assistant, check every fact and every source yourself before submitting.

## Code of conduct

Be kind and constructive. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
