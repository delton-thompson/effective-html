---
name: html-plan
description: Create self-contained HTML implementation plans that are pragmatic, structured, and visually organized with milestones, phases, dependencies, risks, and lightweight diagrams. Use when the user wants a plan, rollout plan, execution plan, implementation roadmap, scoped proposal, or an HTML artifact that explains what to build and in what order without becoming prose heavy.
---

# HTML Plan

Build a single self-contained HTML plan artifact that is practical, visually organized, and easy to scan.

## Workflow

1. Read `references/html-effectiveness/README.md` and `references/html-effectiveness/index.html` first.
2. Review the examples most relevant to planning:
   - `16-implementation-plan.html` for structure and pacing
   - `11-status-report.html` and `12-incident-report.html` for operational information density
   - `13-flowchart-diagram.html` when the plan needs a dependency or flow view
   - Any other example that matches the requested artifact shape
3. Extract the actual execution structure before writing HTML:
   - goals
   - scope / non-goals
   - phases or milestones
   - dependencies
   - risks / open questions
   - success criteria, if useful
4. Build one standalone `.html` file with inline CSS and no build step.
5. Keep the writing concise. Use structure, layout, timelines, chips, tables, and compact diagrams to carry the plan.
6. Prefer decisions and sequencing over generic explanation.

## Output standard

- Make the plan scannable in one pass.
- Surface sequence, ownership, dependencies, and risk clearly.
- Use diagrams when they simplify the plan.
- Keep long prose blocks out of the critical path.
- Make the artifact useful for implementation, not just presentation.

## Planning guidance

- Start with the practical summary: what gets built, in what order, and what can block it.
- Break work into phases that feel executable.
- Use compact status strips, timelines, dependency maps, and callout panels when they help.
- If the user asks for a plan from a prompt or repo context, translate that into concrete milestones and deliverables rather than restating the prompt.
- Keep scope honest; call out what is intentionally deferred when that matters.

## Implementation constraints

- Deliver a single HTML file unless the user asks for another shape.
- Keep everything self-contained.
- Use lightweight diagrams rather than prose where possible.
- Avoid decorative layouts that obscure sequence or priority.

## Reference corpus

This skill bundles the `html-effectiveness` example set under `references/html-effectiveness/`.

- Start with `README.md` and `index.html`.
- Use the planning, report, and diagram examples as compositional references.
- Reuse the patterns that make those examples effective: clear sections, compact labels, restrained palette, and visual sequencing.
