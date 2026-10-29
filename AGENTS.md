# AGENTS.md

## Project
- Wat de site is: website voor CCK (Creative Code Kortrijk), een nieuwe creative coding club in Kortrijk
- Voor wie: bezoekers die info zoeken over CCK: workshops, foundations, het team en nieuws

## Stack & constraints
- Framework: Astro
- Inhoud: beheerd via Astro content collections (`src/content/`)
- Collections: Workshops, Foundations, Team (en later News)
- Schema's staan in `src/content.config.ts`; ontbreekt een veld in een markdown-bestand, dan faalt de build
- Styling: eigen CSS, geen CSS-framework (geen Tailwind, Bootstrap, ...)

