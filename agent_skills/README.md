# Agent Skills and Plugins for the Figma Community

<div align='center'>

_A collection of open source skills and plugins for agents such as Claude, Codex,
Copilot for Figma products._

</div>

## Official Resources

⭐ **[Figma MCP Server Guide](https://github.com/figma/mcp-server-guide)** - Official MCP Server documentation and Agent Plugins registry.

⭐ **[Agent Skills](https://github.com/figma/mcp-server-guide/tree/main/skills)** - Official collection of Figma agent skills.

> Pull Requests are welcome. Please see the [Contributing Guide](../CONTRIBUTING.md) before opening a Pull Request.

This repository is distinct from the [Figma skills page](http://figma.com/community/skills) in the Figma Community. Submitting resources to this repository does not guarantee the resources will be featured in the Figma Community. We'll update the guidance here as we continue to expand the [Figma skills page](http://figma.com/community/skills).

## DISCLAIMER

The resources provided are meant to be helpful for Figma development. They are not
endorsed or sponsored by Figma in any way. **Please do your own due diligence and
security review before using any resources listed.**

---

## Table of Contents
- [AI Behavior](#ai-behavior)
- [Accessibility](#accessibility)
- [Components](#components)
- [Design Generation](#design-generation)
- [Design Process](#design-process)
- [Design Systems](#design-systems)

---

### Accessibility

#### apca-compliance-figma

[SOURCE CODE](https://github.com/Merkle-XDI/apca-compliance-figma) · [MIT](https://github.com/Merkle-XDI/apca-compliance-figma/blob/main/LICENSE.txt)
**MCP Tools:** `get_design_context` `get_variable_defs` `get_screenshot` `use_figma`.
A skill for integrating APCA contrast compliance directly into the Figma design process. Audits and remaps color variables to meet target Lc thresholds, and generates APCA-compliant component variations across light and dark modes.

#### audit-accessibility-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/audit-accessibility-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Produces a per-component accessibility scorecard covering interaction-state coverage, focus indicators, target size, and color-blind simulation.

#### lint-design-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/lint-design-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_metadata`
Lints a node tree against WCAG 2.2 and design-system rules, flagging contrast failures, hardcoded colors and styles, and detached components.

#### scan-code-accessibility-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/scan-code-accessibility-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Runs axe-core against HTML in a JSDOM environment and maps violations back to the originating Figma design.

---

**[⬆ Back to TOC](#table-of-contents)**

### AI Behavior

#### emote-behavioral-contracts

[SOURCE CODE](https://github.com/rogerod/emote-behavioral-contracts) · [MIT](https://github.com/rogerod/emote-behavioral-contracts/blob/main/LICENSE)
**MCP Tools:** `get_design_context` `get_metadata` `use_figma`
Reads Emote behavioral annotation components from a Figma frame and produces implementation-ready behavioral contracts for AI-driven interfaces.

---

**[⬆ Back to TOC](#table-of-contents)**

### Components

#### analyze-component-set-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/analyze-component-set-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_design_context` `get_metadata`
Analyzes a component set as a variant state machine, mapping variant properties to CSS pseudo-classes and reporting per-variant visual differences.

#### arrange-component-set-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/arrange-component-set-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Arranges a component set's variants into a labeled grid on the canvas, parsing variant names into rows and columns.

#### component-properties-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/component-properties-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Defines a component's property API (boolean, text, instance-swap, and variant properties) and instantiates the component with property values applied.

#### deep-component-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/deep-component-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_design_context` `get_metadata`
Walks a component to unlimited depth and returns its full node tree with resolved token bindings, main-component references, and prototype reactions.

#### design-react-api

[SOURCE CODE](https://github.com/bitovi/design-react-api) · [MIT](https://github.com/bitovi/design-react-api/blob/main/LICENSE)
**MCP Tools:** `get_design_context` `get_variable_defs`                                                                          
A spec-driven skill that analyzes a Figma component and proposes a React component API, props interface, TypeScript types, and  
variant-to-prop mappings before any implementation begins.                                                                                       

#### generate-component-doc-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/generate-component-doc-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Generates Markdown documentation for a Figma component, including anatomy, tokens, states, accessibility notes, and design-to-code parity.

#### reconstruct-component-figma

[SOURCE CODE](https://github.com/JP4000000/reconstruct-component-figma) · [MIT](https://github.com/JP4000000/reconstruct-component-figma/blob/main/LICENSE.txt)
**MCP Tools:** `get_design_context` `get_screenshot` `use_figma`
A skill that takes a selected Figma frame and rebuilds it as a proper Atomic Design component system directly on the Figma canvas, without Code Connect or a published library.

---

**[⬆ Back to TOC](#table-of-contents)**

### Design Generation

#### bridge-ds

[SOURCE CODE](https://github.com/noemuch/bridge) · [MIT](https://github.com/noemuch/bridge/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_design_context` `get_screenshot` `get_variable_defs` `search_design_system` `get_metadata`
A skill that generates Figma designs fully bound to your design system. Extracts components, variables, and text styles into a local knowledge base, then compiles declarative scene graphs into Figma Plugin API code executed via MCP. All output uses real component instances, bound variables, and token references — no hardcoded values. Includes a recipe system that learns from corrections to improve future generations.

#### build-slides-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/build-slides-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Authors Figma Slides decks — creating and reordering slides, adding text and shapes, and setting backgrounds, transitions, and view mode.

#### bulk-capture
[SOURCE CODE](https://github.com/tallneil/tallneil-mono-public/tree/main/.claude/skills/bulk-capture) · [CC0](https://github.com/tallneil/tallneil-mono-public/blob/main/LICENSE)
**MCP Tools:** `generate_figma_design` `new_page`

A skill for bulk-capturing many live web app pages into Figma simultaneously using generate_figma_design and Chrome DevTools MCP. Opens all tabs in parallel and polls all capture IDs at once — no manual clicking required.

---

**[⬆ Back to TOC](#table-of-contents)**

### Design Process

#### annotations-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/annotations-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Reads and writes designer annotations and annotation categories on Figma nodes.

#### check-design-parity-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/check-design-parity-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_design_context`
Compares a Figma design node against a code specification and reports drift as scored discrepancies by severity.

#### create-figjam-content

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/create-figjam-content) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Authors and reads FigJam boards — stickies, connectors, shapes with text, sections, tables, and code blocks, with auto-arrange.

#### delight-audit

[SOURCE CODE](https://github.com/mariespreitzer/delight-audit-figma) · [MIT](https://github.com/mariespreitzer/delight-audit-figma/blob/main/LICENSE)
**MCP Tools:** `get_design_context` `get_metadata` `get_screenshot`
Audits Figma designs for emotional quality across three dimensions: unexpected joy, earned satisfaction, and emotional resonance.

#### design-narrative

[SOURCE CODE](https://github.com/mariespreitzer/design-narrative-figma) · [MIT](https://github.com/mariespreitzer/design-narrative-figma/blob/main/LICENSE)
**MCP Tools:** `get_design_context` `get_metadata` `get_screenshot`
Writes a four-part design rationale from a Figma file covering context, insight, design response, and delight intention.

#### screens-to-ia

[SOURCE CODE](https://github.com/mariespreitzer/screens-to-ia-figma) · [MIT](https://github.com/mariespreitzer/screens-to-ia-figma/blob/main/LICENSE)
**MCP Tools:** `get_metadata` `get_design_context` `get_screenshot` `use_figma`
Generates an information architecture page inside the Figma file with a sitemap and per-screen content hierarchy, export-ready as PDF.

#### workshop-board

[SOURCE CODE](https://github.com/mariespreitzer/workshop-board-figma) · [MIT](https://github.com/mariespreitzer/workshop-board-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Generates a complete, ready-to-run FigJam workshop board from a challenge brief, audience, duration, and participant count.

---

**[⬆ Back to TOC](#table-of-contents)**

### Design Systems

#### design-system-inventory-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/design-system-inventory-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_design_context` `get_metadata`
Extracts a unified inventory of a file's variables, components, and styles with resolved visual specifications and adaptive compression.

#### ds-init-figma

[SOURCE CODE](https://github.com/arnaudmorvan/ds-init-figma) · [MIT](https://github.com/arnaudmorvan/ds-init-figma/blob/main/LICENSE)
**MCP Tools:** `create_new_file` `use_figma` `get_screenshot`
A skill that creates a complete Design System directly on the Figma canvas, including variables, tokens, foundations, components with variants, documentation pages, and showcase layouts. Supports full DS creation, adding individual components, or generating specific pages on an existing file.

#### ds-compliance-audit
[SOURCE CODE](https://github.com/namikazeseb/ds-compliance-audit) · [CC0](https://creativecommons.org/publicdomain/zero/1.0/)
**MCP Tools:** `use_figma`

Audits Figma screens for design system compliance.
Detects incorrect components, missing token bindings, spacing violations, typography drift, and accessibility issues.
Outputs structured audit report with fixes.

#### export-tokens-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/export-tokens-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_variable_defs`
Exports Figma variables to design token files in DTCG, CSS custom properties, Tailwind, SCSS, TypeScript, JSON, Style Dictionary, or Tokens Studio formats, with multi-mode and alias resolution. Works on any Figma plan.

#### generate-tokens-from-figma

[SOURCE CODE](https://github.com/congemcd/skills-collection/tree/main/skills/generate-tokens-from-figma) · [MIT](https://github.com/congemcd/skills-collection/blob/main/LICENSE)
**MCP Tools:** `use_figma`

Generates design token reports and DTCG token files from Figma variables and styles.

#### import-tokens-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/import-tokens-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_variable_defs`
Creates and updates Figma variables from DTCG token files, with multi-mode values, alias resolution, and non-destructive matching so re-imports update in place.

#### library-variables-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/library-variables-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Discovers variables available from subscribed team libraries and imports them into the current file by key.

#### manage-variables-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/manage-variables-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_variable_defs`
Performs create, update, rename, and delete operations on Figma variables, collections, and modes, including batch creation and updates.

#### setup-design-tokens-figma

[SOURCE CODE](https://github.com/southleft/skills-for-figma/tree/main/skills/setup-design-tokens-figma) · [MIT](https://github.com/southleft/skills-for-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma` `get_variable_defs`
Bootstraps a complete token system — a collection, its modes, and all variables with per-mode values — in a single atomic operation.

---

**[⬆ Back to TOC](#table-of-contents)**
