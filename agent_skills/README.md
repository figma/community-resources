# Agent Skills and Plugins for the Figma Community

<div align='center'>

_A collection of open source skills and plugins for agents such as Claude, Codex,
Copilot for Figma products._

</div>

> Pull Requests are welcome. Please see the [Contributing Guide](../CONTRIBUTING.md) before opening a Pull Request.

This repository is distinct from the [Figma skills page](http://figma.com/community/skills) in the Figma Community. Submitting resources to this repository does not guarantee the resources will be featured in the Figma Community. We'll update the guidance here as we continue to expand the [Figma skills page](http://figma.com/community/skills).

## DISCLAIMER

The resources provided are meant to be helpful for Figma development. They are not
endorsed or sponsored by Figma in any way. **Please do your own due diligence and
security review before using any resources listed.**

---

## Table of Contents

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

---

**[⬆ Back to TOC](#table-of-contents)**

### Components

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

---

**[⬆ Back to TOC](#table-of-contents)**

### Design Process

#### delight-audit

[SOURCE CODE](https://github.com/mariespreitzer/delight-audit-figma) · [MIT](https://github.com/mariespreitzer/delight-audit-figma/blob/main/LICENSE)
**MCP Tools:** `get_design_context` `get_metadata` `get_screenshot`
Audits Figma designs for emotional quality across three dimensions: unexpected joy, earned satisfaction, and emotional resonance.

---

#### design-narrative

[SOURCE CODE](https://github.com/mariespreitzer/design-narrative-figma) · [MIT](https://github.com/mariespreitzer/design-narrative-figma/blob/main/LICENSE)
**MCP Tools:** `get_design_context` `get_metadata` `get_screenshot`
Writes a four-part design rationale from a Figma file covering context, insight, design response, and delight intention.

---

#### screens-to-ia

[SOURCE CODE](https://github.com/mariespreitzer/screens-to-ia-figma) · [MIT](https://github.com/mariespreitzer/screens-to-ia-figma/blob/main/LICENSE)
**MCP Tools:** `get_metadata` `get_design_context` `get_screenshot` `use_figma`
Generates an information architecture page inside the Figma file with a sitemap and per-screen content hierarchy, export-ready as PDF.

---

#### workshop-board

[SOURCE CODE](https://github.com/mariespreitzer/workshop-board-figma) · [MIT](https://github.com/mariespreitzer/workshop-board-figma/blob/main/LICENSE)
**MCP Tools:** `use_figma`
Generates a complete, ready-to-run FigJam workshop board from a challenge brief, audience, duration, and participant count.

---

**[⬆ Back to TOC](#table-of-contents)**

### Design Systems

#### ds-init-figma

[SOURCE CODE](https://github.com/arnaudmorvan/ds-init-figma) · [MIT](https://github.com/arnaudmorvan/ds-init-figma/blob/main/LICENSE)
**MCP Tools:** `create_new_file` `use_figma` `get_screenshot`
A skill that creates a complete Design System directly on the Figma canvas, including variables, tokens, foundations, components with variants, documentation pages, and showcase layouts. Supports full DS creation, adding individual components, or generating specific pages on an existing file.

---

**[⬆ Back to TOC](#table-of-contents)**
