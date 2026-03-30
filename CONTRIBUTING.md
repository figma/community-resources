# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms. Please note that Figma reserves the right to accept / reject any resource at its discretion.

## Resource Guidelines

### Requirements

- [ ] This pull request has a title in the format `Add [TYPE] NAME_OF_RESOURCE`.
  - ✅ `Add [plugin] Design Lint`
  - ✅ `Add [widget] Sticky Notes Exporter`
  - ✅ `Add [skill] figma-implement-design`
  - ✅ `Add [resource] create-figma-plugin`
  - ❌ `Update readme.md`
- [ ] Your entry here should include a short description about the resource. The first character should be uppercase and the description should end in a dot. It should be an objective description and not a tagline or marketing blurb.
  - ✅ `- A small lightweight design system for use in Figma Plugins`
  - ✅ `- A Figma plugin for creating bulk color styles from selection.`
  - ❌ `- The best Figma plugin`
  - ❌ `- This resource will change your life.`
- [ ] The name of your resource shouldn't start with Figma.
  - See our [brand usage guidelines](https://www.figma.com/using-the-figma-brand/#indicating-compatibility).
  - Example of good names: Easy Token Reference, color-sync-figma.
  - Example of bad names: Figma Style Tool, figma-code-convert.
- [ ] Your entry should be added to the appropriate section file sorted in alphabetical order.
- [ ] Your entry should be in the following format.
- [ ] Your entry is an active project - outdated projects will not be accepted.
- [ ] If possible, your resource should have an appropriate license.
  - **We strongly recommend the [CC0 license](https://creativecommons.org/publicdomain/zero/1.0/), but any [Creative Commons license](https://creativecommons.org/choose/) will work.**
    - Tip: You can quickly add it to your repo by going to this URL: `https://github.com/<user>/<repo>/community/license/new?branch=main&template=cc0-1.0` (replace `<user>` and `<repo>` accordingly).
  - A code license like MIT is acceptable.
  - Place a file named `license` or `LICENSE` in the repo root with the license text.
- [ ] The repo should have the appropriate [GitHub topics](https://help.github.com/articles/about-topics) based on resource type:
  - **Plugins:** `figma` + `figma-plugin`
  - **Widgets:** `figma` + `figma-widget`
  - **Skills:** `figma` + `figma-mcp`
  - **Resources:** `figma` + the most relevant type tag
- [ ] By submitting a link you represent that to the best of your knowledge you are not infringing another party's intellectual party.
- [ ] Your entry should be in the following format

  - Plugin:

    ```
    #### PLUGIN_NAME
    [SOURCE CODE](GITHUB_URL) · [PLUGIN](FIGMA_PLUGIN_URL) · [LICENSE_TYPE](LICENSE_URL)

    Plugin description.
    ```

  - Widget:

    ```
    #### WIDGET_NAME
    [SOURCE CODE](GITHUB_URL) · [WIDGET](FIGMA_WIDGET_URL) · [LICENSE_TYPE](LICENSE_URL)

    Widget description.
    ```

  - Skill:

    ```
    #### SKILL_NAME
    [SOURCE CODE](GITHUB_URL) · [LICENSE_TYPE](LICENSE_URL)
    **MCP Tools:** `tool_a` `tool_b` `tool_c`

    Skill description.
    ```

  - Resource:

    ```
    #### RESOURCE_NAME
    [SOURCE CODE](GITHUB_URL) · [LICENSE_TYPE](LICENSE_URL)

    Resource description.
    ```
