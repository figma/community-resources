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

#### design-react-api

[SOURCE CODE](https://github.com/bitovi/design-react-api) · [MIT](https://github.com/bitovi/design-react-api/blob/main/LICENSE)
**MCP Tools:** `get_design_context` `get_variable_defs`                                                                          
A spec-driven skill that analyzes a Figma component and proposes a React component API, props interface, TypeScript types, and  
variant-to-prop mappings before any implementation begins.                                                                                       
                                                                                                                               
---

#### reconstruct-component-figma

[SOURCE CODE](https://github.com/JP4000000/reconstruct-component-figma) · [MIT](https://github.com/JP4000000/reconstruct-component-figma/blob/main/LICENSE.txt)
**MCP Tools:** `get_design_context` `get_screenshot` `use_figma`
A skill that takes a selected Figma frame and rebuilds it as a proper Atomic Design component system directly on the Figma canvas, without Code Connect or a published library.

---

**[⬆ Back to TOC](#table-of-contents)**

### Design Systems

#### ds-init-figma

[SOURCE CODE](https://github.com/arnaudmorvan/ds-init-figma) · [MIT](https://github.com/arnaudmorvan/ds-init-figma/blob/main/LICENSE)
**MCP Tools:** `create_new_file` `use_figma` `get_screenshot`
A skill that creates a complete Design System directly on the Figma canvas, including variables, tokens, foundations, components with variants, documentation pages, and showcase layouts. Supports full DS creation, adding individual components, or generating specific pages on an existing file.

---

**[⬆ Back to TOC](#table-of-contents)**
