<div align="center">

# boardroom

**Les frameworks d'école de commerce, sous forme de skills pour votre agent IA.**

SWOT · 5 forces de Porter · BCG · Ansoff · Océan bleu · Business Model Canvas · TAM/SAM/SOM · Économie unitaire · et d'autres

[![Licence : MIT](https://img.shields.io/badge/licence-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-16-black.svg)](#les-skills)
[![Langues](https://img.shields.io/badge/langues-EN%20%7C%20FR%20%7C%20ES-green.svg)](#fonctionne-en-anglais-en-français-et-en-espagnol)
[![PR bienvenues](https://img.shields.io/badge/PR-bienvenues-brightgreen.svg)](CONTRIBUTING.md)

[English](README.md) · **Français** · [Español](README.es.md)

</div>

---

Demandez un SWOT à un agent IA et vous obtiendrez souvent quatre listes génériques qui pourraient décrire n'importe quelle entreprise. Demandez-lui la taille d'un marché et il vous donnera, sans hésiter, un chiffre sorti de nulle part.

**boardroom** donne à votre agent la méthode qu'attendrait un professeur de stratégie exigeant : un périmètre précis, une preuve pour chaque affirmation, des hypothèses signalées comme telles au lieu de chiffres inventés, un « so what » pour chaque constat et, pour finir, une recommandation claire.

## Installation

**La plupart des agents de code** (Claude Code, Codex, Cursor, Windsurf, Cline et d'autres) :

```bash
npx skills add teodstr/boardroom -g
```

**Claude Code**, sous forme de plugin :

```
/plugin marketplace add teodstr/boardroom
/plugin install boardroom@boardroom
```

**À la main :** copiez les dossiers de [`skills/`](skills) dans le dossier de skills de votre agent.

## Utilisation

Posez simplement votre question. Le bon skill se charge tout seul.

```
We run 12 bakeries in Bordeaux. Should we open in Toulouse or launch delivery first?
Fais-moi une analyse PESTEL du marché du vin bio en Allemagne.
Haz un DAFO de Zara frente a Shein y propón una estrategia.
What are the unit economics of a meal-kit subscription at €60 a box?
```

## Les skills

| Skill | Framework | Pour quoi faire |
|---|---|---|
| [`business-analysis`](skills/business-analysis/SKILL.md) | Arbre des problèmes, SCQA, principe de la pyramide | Études de cas et questions de stratégie ouvertes : choisit les frameworks et conclut par une recommandation |
| [`swot-tows`](skills/swot-tows/SKILL.md) | SWOT + matrice TOWS | Un diagnostic de la situation qui débouche sur des options stratégiques |
| [`pestel`](skills/pestel/SKILL.md) | PESTEL | Le macro-environnement d'un marché ou d'un pays |
| [`porter-five-forces`](skills/porter-five-forces/SKILL.md) | 5 forces de Porter | L'attractivité d'un secteur et l'intensité concurrentielle |
| [`vrio`](skills/vrio/SKILL.md) | VRIO | L'avantage concurrentiel durable |
| [`ansoff-matrix`](skills/ansoff-matrix/SKILL.md) | Matrice d'Ansoff | Les options de croissance et leur risque |
| [`bcg-matrix`](skills/bcg-matrix/SKILL.md) | Matrice BCG | Un portefeuille de produits ou de domaines d'activité |
| [`business-model-canvas`](skills/business-model-canvas/SKILL.md) | Business Model Canvas, Value Proposition Canvas | La façon dont une entreprise crée et capte de la valeur |
| [`blue-ocean`](skills/blue-ocean/SKILL.md) | Canevas stratégique, grille ERRC | Sortir de la concurrence frontale |
| [`market-sizing`](skills/market-sizing/SKILL.md) | TAM / SAM / SOM | La taille d'un marché, par approche descendante et ascendante |
| [`unit-economics`](skills/unit-economics/SKILL.md) | CAC, LTV, délai de récupération, seuil de rentabilité | La rentabilité par client ou par unité |
| [`stp-positioning`](skills/stp-positioning/SKILL.md) | Segmentation, ciblage, positionnement | Choisir une cible et un positionnement |
| [`marketing-mix`](skills/marketing-mix/SKILL.md) | 4P / 7P | Des plans marketing et des plans de lancement cohérents |
| [`supply-chain-strategy`](skills/supply-chain-strategy/SKILL.md) | Modèle de Fisher, grille d'incertitude de Lee | Une supply chain lean ou agile |
| [`crisis-communication`](skills/crisis-communication/SKILL.md) | SCCT | Réponse à une crise, communiqués, plan par partie prenante |
| [`luxury-brand-strategy`](skills/luxury-brand-strategy/SKILL.md) | Prisme d'identité de Kapferer, règles du luxe | Marques de luxe et marques premium |

## Ce que chaque skill impose

- **Un périmètre précis.** « Les voitures électriques premium en Europe », pas « les voitures ».
- **Une preuve ou une étiquette.** Chaque affirmation vient de vos documents, d'une source ou d'une hypothèse clairement signalée. Aucune statistique inventée.
- **Le « so what ».** Chaque constat dit ce qu'il change pour la décision.
- **Une recommandation.** Une analyse se termine par une décision et des prochaines étapes, pas par une matrice.
- **De vraies sources.** Chaque skill cite les auteurs d'origine (Porter, Barney, Kim et Mauborgne, Osterwalder…).

## Fonctionne en anglais, en français et en espagnol

Posez votre question dans l'une des trois langues et l'agent répond avec les termes réellement employés en école de commerce : *analyse SWOT* en français, *DAFO* en Espagne et *FODA* en Amérique latine, *les 5 forces de Porter*, *las cinco fuerzas de Porter*, *vaches à lait*, *vacas lecheras*… Chaque skill se termine par un tableau de terminologie, et ajouter une langue est l'une des façons les plus simples de contribuer.

## Contribuer

boardroom est pensé pour que tout le monde puisse contribuer, même sans avoir jamais écrit une ligne de code : un skill tient dans un seul fichier Markdown.

- **Ajoutez un framework** de la [feuille de route](ROADMAP.md) : McKinsey 7S, chaîne de valeur, Balanced Scorecard, Lean Canvas, Hofstede, Kotter…
- **Ajoutez une langue** aux tableaux de terminologie (allemand, italien, portugais…) ou traduisez ce README.
- **Améliorez un skill** avec une étape plus claire, une erreur fréquente à éviter ou une meilleure source.
- **Signalez une réponse faible :** ouvrez une issue avec votre prompt et ce que l'agent a produit.

Commencez par [CONTRIBUTING.md](CONTRIBUTING.md) (en anglais). Chaque pull request est vérifiée automatiquement.

## Licence

[MIT](LICENSE). Maintenu par [teodstr](https://github.com/teodstr), qui étudie en école de commerce. Réalisé avec l'aide de Claude.
