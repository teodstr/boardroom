<div align="center">

# boardroom

**Los frameworks de las escuelas de negocios, como skills para tu agente de IA.**

DAFO/FODA · Cinco fuerzas de Porter · BCG · Ansoff · Océano azul · Business Model Canvas · TAM/SAM/SOM · Economía unitaria · y más

[![Licencia: MIT](https://img.shields.io/badge/licencia-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-16-black.svg)](#las-skills)
[![Idiomas](https://img.shields.io/badge/idiomas-EN%20%7C%20FR%20%7C%20ES-green.svg)](#funciona-en-inglés-francés-y-español)
[![PR bienvenidas](https://img.shields.io/badge/PR-bienvenidas-brightgreen.svg)](CONTRIBUTING.md)

[English](README.md) · [Français](README.fr.md) · **Español**

</div>

---

Pídele un DAFO a un agente de IA y lo normal es que te dé cuatro listas genéricas que valdrían para cualquier empresa. Pídele el tamaño de un mercado y te dará, sin dudarlo, una cifra sacada de la nada.

**boardroom** le da a tu agente el método que esperaría un profesor de estrategia exigente: un alcance preciso, pruebas para cada afirmación, supuestos señalados como tales en lugar de cifras inventadas, un «so what» para cada hallazgo y, al final, una recomendación clara.

## Instalación

**La mayoría de los agentes de programación** (Claude Code, Codex, Cursor, Windsurf, Cline y otros):

```bash
npx skills add teodstr/boardroom -g
```

**Claude Code**, como plugin:

```
/plugin marketplace add teodstr/boardroom
/plugin install boardroom@boardroom
```

**A mano:** copia las carpetas de [`skills/`](skills) en la carpeta de skills de tu agente.

## Uso

Pregunta sin más. La skill adecuada se carga sola.

```
We run 12 bakeries in Bordeaux. Should we open in Toulouse or launch delivery first?
Fais-moi une analyse PESTEL du marché du vin bio en Allemagne.
Haz un DAFO de Zara frente a Shein y propón una estrategia.
What are the unit economics of a meal-kit subscription at €60 a box?
```

## Las skills

| Skill | Framework | Para qué sirve |
|---|---|---|
| [`business-analysis`](skills/business-analysis/SKILL.md) | Árbol de problemas, SCQA, principio de la pirámide | Casos prácticos y preguntas abiertas de estrategia: elige los frameworks y termina con una recomendación |
| [`swot-tows`](skills/swot-tows/SKILL.md) | DAFO/FODA + matriz TOWS | Un análisis de la situación que se traduce en opciones estratégicas |
| [`pestel`](skills/pestel/SKILL.md) | PESTEL | El macroentorno de un mercado o de un país |
| [`porter-five-forces`](skills/porter-five-forces/SKILL.md) | Cinco fuerzas de Porter | El atractivo de un sector y su competencia |
| [`vrio`](skills/vrio/SKILL.md) | VRIO | La ventaja competitiva sostenible |
| [`ansoff-matrix`](skills/ansoff-matrix/SKILL.md) | Matriz de Ansoff | Las opciones de crecimiento y su riesgo |
| [`bcg-matrix`](skills/bcg-matrix/SKILL.md) | Matriz BCG | Una cartera de productos o de unidades de negocio |
| [`business-model-canvas`](skills/business-model-canvas/SKILL.md) | Business Model Canvas, Value Proposition Canvas | Cómo una empresa crea y captura valor |
| [`blue-ocean`](skills/blue-ocean/SKILL.md) | Cuadro estratégico, matriz ERRC | Salir de la competencia directa |
| [`market-sizing`](skills/market-sizing/SKILL.md) | TAM / SAM / SOM | El tamaño de un mercado, con enfoque descendente y ascendente |
| [`unit-economics`](skills/unit-economics/SKILL.md) | CAC, LTV, periodo de recuperación, punto de equilibrio | La rentabilidad por cliente o por unidad |
| [`stp-positioning`](skills/stp-positioning/SKILL.md) | Segmentación, público objetivo, posicionamiento | Elegir un público objetivo y un posicionamiento |
| [`marketing-mix`](skills/marketing-mix/SKILL.md) | 4P / 7P | Planes de marketing y de lanzamiento coherentes |
| [`supply-chain-strategy`](skills/supply-chain-strategy/SKILL.md) | Modelo de Fisher, marco de incertidumbre de Lee | Una cadena de suministro eficiente (lean) o ágil |
| [`crisis-communication`](skills/crisis-communication/SKILL.md) | SCCT | Respuesta a una crisis, comunicados, plan por grupo de interés |
| [`luxury-brand-strategy`](skills/luxury-brand-strategy/SKILL.md) | Prisma de identidad de Kapferer, reglas del lujo | Marcas de lujo y marcas premium |

## Lo que exige cada skill

- **Un alcance preciso.** «Coches eléctricos premium en Europa», no «coches».
- **Una prueba o una etiqueta.** Cada afirmación procede de tu material, de una fuente o de un supuesto claramente señalado. Ninguna estadística inventada.
- **El «so what».** Cada hallazgo dice qué cambia para la decisión.
- **Una recomendación.** Un análisis termina con una decisión y los próximos pasos, no con una matriz.
- **Fuentes reales.** Cada skill cita a los autores originales (Porter, Barney, Kim y Mauborgne, Osterwalder…).

## Funciona en inglés, francés y español

Pregunta en cualquiera de los tres idiomas y el agente responde con los términos que de verdad se usan en las escuelas de negocios: *analyse SWOT* en francés, *DAFO* en España y *FODA* en Latinoamérica, *les 5 forces de Porter*, *las cinco fuerzas de Porter*, *vaches à lait*, *vacas lecheras*… Cada skill termina con una tabla de terminología, y añadir un idioma es una de las formas más sencillas de contribuir.

## Contribuir

boardroom está pensado para que cualquiera pueda contribuir, aunque nunca haya escrito una línea de código: una skill es un solo archivo Markdown.

- **Añade un framework** de la [hoja de ruta](ROADMAP.md): McKinsey 7S, cadena de valor, Balanced Scorecard, Lean Canvas, Hofstede, Kotter…
- **Añade un idioma** a las tablas de terminología (alemán, italiano, portugués…) o traduce este README.
- **Mejora una skill** con un paso más claro, un error frecuente que evitar o una fuente mejor.
- **Informa de una respuesta floja:** abre un issue con tu prompt y lo que produjo el agente.

Empieza por [CONTRIBUTING.md](CONTRIBUTING.md) (en inglés). Cada pull request se comprueba automáticamente.

## Licencia

[MIT](LICENSE). Mantenido por [teodstr](https://github.com/teodstr), que estudia en una escuela de negocios. Hecho con la ayuda de Claude.
