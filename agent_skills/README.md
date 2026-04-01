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
A compiler-driven design generation skill that produces 100% design-system-compliant Figma designs. Extracts your design system into a knowledge base, compiles declarative scene graphs with token references into Figma Plugin API code, and executes it via MCP. Supports components, bound variables, text styles, and recipe-based iteration.

---

**[⬆ Back to TOC](#table-of-contents)**
