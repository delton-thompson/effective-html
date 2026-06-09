## HTML skills for pragmatic visual artifacts

Two focused skills for generating self-contained HTML deliverables with a strong visual bias:

- `html-diagram`: architecture, stack, and systems understanding rendered as full-screen HTML diagrams with high-quality SVG
- `html-plan`: implementation plans rendered as pragmatic HTML pages with milestones, sequencing, risks, and just enough explanatory text

## Install

```bash
npx skills add plannotator/effective-html
```

List available skills first:

```bash
npx skills add plannotator/effective-html --list
```

Install a specific skill:

```bash
npx skills add plannotator/effective-html --skill html-diagram
npx skills add plannotator/effective-html --skill html-plan
```

## Skills

- `html-diagram` - Build full-screen HTML architecture and stack diagrams with SVG-first presentation and minimal prose.
- `html-plan` - Build pragmatic HTML implementation plans with structure, sequencing, and lightweight diagrams.

## Repository Shape

Skills live under `skills/<skill-name>/SKILL.md`. Each skill also bundles a copy of the `html-effectiveness` example corpus under `references/html-effectiveness/` so the examples stay local to the skill.
