---
name: html-diagram
description: Create self-contained HTML files for architecture, system, stack, and codebase understanding with SVG-first diagrams and minimal prose. Use when the user wants a visual explainer, architecture view, stack overview, flow diagram, full-screen diagram, system map, or wants an HTML artifact focused on understanding relationships rather than reading dense text.
---

# HTML Diagram

Build a single self-contained HTML artifact that is visually led, not prose led.

## Workflow

1. Read `references/html-effectiveness/README.md` and `references/html-effectiveness/index.html` first.
2. Review the relevant examples before designing:
   - `13-flowchart-diagram.html` for architecture and flow layout
   - `04-code-understanding.html` for codebase/system understanding
   - `10-svg-illustrations.html` for SVG craft and palette discipline
   - Any other nearby example that matches the requested output shape
3. Infer the diagram's information architecture before writing HTML:
   - main entities
   - edges / relationships
   - grouping / layers
   - interaction, if any
4. Build one standalone `.html` file with inline CSS and inline SVG. Do not require a build step.
5. Keep prose light. The page should read primarily as a diagram, labels, legends, and compact annotations.
6. Iterate on spacing, alignment, stroke hierarchy, and label clarity until the diagram carries the explanation.

## Output standard

- Prefer a full-screen or near-full-screen composition.
- Make SVG the primary medium for the architecture view.
- Use restrained typography and a tight palette.
- Keep text short, scannable, and subordinate to the visual structure.
- Use legends, chips, and callouts only when they reduce ambiguity.
- Avoid turning the page into a long memo with a diagram attached.

## Diagram guidance

- Show structure first, detail second.
- Use layout to communicate hierarchy: layers, lanes, clusters, ownership boundaries, and flow direction.
- Prefer direct labels on nodes and edges over long explanatory paragraphs.
- Make the "what talks to what" and "where responsibility lives" obvious at a glance.
- If the request is about architecture or stack understanding, include the actual stack/components, not abstract placeholders.
- If interaction helps, keep it lightweight and supportive, such as hover details or a small side panel.

## Implementation constraints

- Deliver a single HTML file unless the user asks for another shape.
- Keep assets inline when possible.
- Use semantic HTML around the diagram, but let the SVG carry most of the information.
- Avoid decorative filler that does not improve comprehension.

## Reference corpus

This skill bundles the `html-effectiveness` example set under `references/html-effectiveness/`.

- Start with `README.md` and `index.html` to understand the gallery.
- Then inspect the specific example files that match the requested diagram style.
- The files are local references. Reuse their composition patterns, not their fictional subject matter.
