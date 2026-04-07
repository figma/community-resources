<div align='center'>

# Open Source Resources for Figma Plugin and Widget Development

_A collection of open source plugins and resources for Figma + FigJam that have been shared on GitHub._

</div>

## Official Resources

⭐ **[Plugin Samples](https://github.com/figma/plugin-samples)** - Official Figma plugin samples and examples from the Figma team.

> _Pull Requests are being welcomed. Please see the [Contributing Guide](../CONTRIBUTING.md) before opening a Pull Request._

This repository is distinct from the [Figma plugins page](https://www.figma.com/community/plugins) in the Figma Community. Submitting resources to this repository does not guarantee the resources will be featured in the Figma Community. To learn about submitting to the Figma Community, see [Publish plugins to the Figma Community](https://help.figma.com/hc/en-us/articles/360042293394).

## DISCLAIMER:

The resources provided are meant to be helpful for Figma plugin development. They are not endorsed or sponsored by Figma in any way. **Please do your own due diligence and security review before using any resources listed.**

---

## Table of Contents

- [Resources](#resources) -- Resources for building plugins and widgets
  - [Starter Templates](#starter-templates)
  - [Design System Components](#design-system-components)
  - [Helper Functions](#helper-functions)
  - [CI/CD Release Tools](#cicd-release-tools)
- [Plugins](#plugins) -- Plugin Source Code
  - [Accessibility](#accessibility)
  - [Color](#color)
  - [Design Linters](#design-linters)
  - [Design Systems](#design-systems)
  - [Developer Tools](#developer-tools)
  - [Export](#export)
  - [Icons](#icons)
  - [Maps](#maps)
  - [Organization](#organization)
  - [Responsive](#responsive)
  - [Text](#text)
  - [Utilities](#utilities)
  - [Misc](#misc)

---

## Resources

A collection of resources to help accelerate the development process of Figma plugins and widgets.

---

### Starter Templates

These starter templates package the boilerplate needed to develop plugins and widgets.

#### Create Figma Plugin

[SOURCE CODE](https://github.com/yuanqing/create-figma-plugin) · [MIT](https://github.com/yuanqing/create-figma-plugin/blob/main/LICENSE.md)

🔋 The comprehensive toolkit for developing plugins and widgets for Figma and FigJam

---

#### FigPlug

[SOURCE CODE](https://github.com/rsms/figplug) · [MIT](https://github.com/rsms/figplug/blob/master/LICENSE)

figplug is a small program for building Figma plugins. It offers all the things you need for most projects: TypeScript, React/JSX, asset bundling, plugin manifest generation, etc.

---

#### Plugma

[SOURCE CODE](https://github.com/gavinmcfarland/plugma) · [MIT](https://github.com/gavinmcfarland/plugma/blob/main/LICENCE.md)

Plugma is a community-created toolkit to create plugins with support for common frameworks and additional development tools. For more information on what Plugma offers you can [visit their documentation](https://www.plugma.dev/docs/getting-started).

---

#### Figma Plugin React Template

[SOURCE CODE](https://github.com/nirsky/figma-plugin-react-template) · NO LICENSE

Quickstart your Figma Plugin with this template and tooling.

---

#### Figsvelte

[SOURCE CODE](https://github.com/thomas-lowry/figsvelte) · [MIT](https://github.com/thomas-lowry/figsvelte/blob/master/LICENSE)

A boilerplate for creating Figma plugins using Svelte.

---

#### Figma Plugin Template

[SOURCE CODE](https://github.com/tomquinonero/figma-plugin-template) · NO LICENSE

A Figma plugin template using svelte. SCSS and Typescript support

---

#### fwidgets

[SOURCE CODE](https://github.com/fwextensions/fwidgets) · [MIT](https://github.com/fwextensions/fwidgets/blob/main/LICENSE)

The fastest way to create a Figma plugin UI — with zero UI code.

---

**[⬆ Back to TOC](#table-of-contents)**

### Design System Components

#### Figma Kit

[SOURCE CODE](https://github.com/tigranpetrossian/figma-kit) · [MIT](https://github.com/tigranpetrossian/figma-kit/blob/beta/LICENSE)

An extensive set of React components for building Figma plugins. UI3-ready, first-class Tailwind support.

#### Figma Plugin DS Svelte

[SOURCE CODE](https://github.com/thomas-lowry/figma-plugin-ds-svelte) · [MIT](https://github.com/thomas-lowry/figma-plugin-ds-svelte/blob/master/LICENSE)

Figma Plugin DS components made with Svelte

---

#### Figma Plugin DS

[SOURCE CODE](https://github.com/thomas-lowry/figma-plugin-ds) · [MIT](https://github.com/thomas-lowry/figma-plugin-ds/blob/master/LICENSE)

A small lightweight design system for use in Figma Plugins

---

#### React Figma Plugin DS

[SOURCE CODE](https://github.com/alexandrtovmach/react-figma-plugin-ds) · [MIT](https://github.com/alexandrtovmach/react-figma-plugin-ds/blob/master/LICENSE)

React components of Figma design system

---

**[⬆ Back to TOC](#table-of-contents)**

### Helper Functions

#### figma-await-ipc

[SOURCE CODE](https://github.com/fwextensions/figma-await-ipc) · [MIT](https://github.com/fwextensions/figma-await-ipc/blob/main/LICENSE)

A simple `await`-able replacement for `postMessage()` in Figma plugins.

---

#### Figma Plugin Helpers

[SOURCE CODE](https://github.com/figma-plugin-helper-functions/figma-plugin-helpers) · NO LICENSE

A collection of useful helper functions to import to your Figma plugin project

**[⬆ Back to TOC](#table-of-contents)**

---

### CI/CD Release Tools

#### figcd

[SOURCE CODE](https://github.com/parrot-global/figcd) · [MIT](https://github.com/parrot-global/figcd/blob/main/LICENSE)

A CLI tool for seamless continuous delivery of Figma plugins. Inspired by Fastlane, figcd streamlines the manual process of publishing Figma plugins.

#### figma-plugin-deploy

[SOURCE CODE](https://github.com/typper-io/figma-plugin-deploy) · [MIT](https://github.com/typper-io/figma-plugin-deploy/blob/main/LICENSE)

A GitHub Action to automate the deployment of Figma plugins. This action handles the entire deployment process, from authentication to publishing, making continuous deployment of Figma plugins seamless and efficient.

**[⬆ Back to TOC](#table-of-contents)**

---

## Plugins

A collection of plugins that have been open-sourced. You can install these plugins, audit them or fork your own if you want to host your own.

---

### Accessibility

#### Include

[SOURCE CODE](https://github.com/eBay/figma-include-accessibility-annotations) · [PLUGIN](https://www.figma.com/community/plugin/1208180794570801545/includeaccessibility-annotations) · [APACHE LICENSE 2.0](https://github.com/eBay/figma-include-accessibility-annotations/blob/main/LICENSE)

Include is a Figma plugin that simplifies annotating for accessibility (a11y). It makes it easier for designers to spec and easier for developers to understand what is required.

---

#### Polychrom

[SOURCE CODE](https://github.com/evilmartians/figma-polychrom) · [PLUGIN](https://www.figma.com/community/plugin/1281280685402026529/polychrom) · [MIT](https://github.com/evilmartians/figma-polychrom/blob/main/LICENSE)

Polychrom is a Figma plugin that allows users to measure contrast levels between selected layers, providing instant feedback. It uses the APCA method to determine contrast, provides text size recommendations, and converts colors to various formats, including OKLCH, RGB, and HEX for easy CSS code copying.

---

#### zebra

[SOURCE CODE](https://github.com/danhollick/zebra) · [PLUGIN](https://www.figma.com/c/plugin/806578669827234193/zebra) · NO LICENSE

Zebra is a fast, lightweight colour contrast checker.

---

**[⬆ Back to TOC](#table-of-contents)**

### Color

#### Chroma

[SOURCE CODE](https://github.com/kaleidocode-app/chroma) · [PLUGIN](https://www.figma.com/c/plugin/739237058450529919/Chroma-Colors) · [MIT](https://github.com/kaleidocode-app/chroma/blob/master/LICENSE)

A Figma plugin for creating bulk color styles from selection.

---

#### Dominant Color

[SOURCE CODE](https://github.com/brianlovin/figma-dominant-color-toolkit) · [PLUGIN](https://www.figma.com/community/plugin/744725347356614754/Dominant-Color-Toolkit-%F0%9F%8E%A8) · [MIT](https://github.com/brianlovin/figma-dominant-color-toolkit/blob/main/LICENSE)

Generate a palette from an image to magically populate your designs.

---

#### Easing Gradient

[SOURCE CODE](https://github.com/alexwidua/figma-easing-gradients) · [PLUGIN](https://www.figma.com/c/plugin/781591244449826498/Easing-Gradient) · [MIT](https://github.com/alexwidua/figma-easing-gradients/blob/master/LICENSE)

Make beautiful smooth gradients in Figma. Linear gradients often have hard edges where they start and/or end. This plugin adds gradient stops to approximate easing functions.

---

#### Lucidi

[SOURCE CODE](https://github.com/dimuuu/lucidi) · [PLUGIN](https://www.figma.com/community/plugin/1235943434768675768) · [CC0](https://github.com/dimuuu/lucidi/blob/main/LICENSE)

Create & sync opacity styles based on primary opaque color styles.

---

#### Navigator

[SOURCE CODE](https://github.com/kaleidocode-app/navigator) · [PLUGIN](https://www.figma.com/c/plugin/739558587628004077/Navigator) · NO LICENSE

An easy way to find and apply color styles from your current document.

---

#### system.colors()

[SOURCE CODE](https://github.com/thelittlewonder/system.colors) · [PLUGIN](https://www.figma.com/community/plugin/832358256915224919) · NO LICENSE

Import color palettes from popular design systems directly to your file.

---

#### Valor

[SOURCE CODE](https://github.com/kolebayev/valor-figma-plugin) · [PLUGIN](https://www.figma.com/community/plugin/798588768596541799/Valor) · NO LICENSE

Visualise existing or new color palettes in your design system or Generate lists of color variables from color palettes.

---

**[⬆ Back to TOC](#table-of-contents)**

### Design Linters

#### Design Lint

[SOURCE CODE](https://github.com/destefanis/design-lint) · [PLUGIN](https://www.figma.com/c/plugin/801195587640428208/Design-Lint) · [MIT](https://github.com/destefanis/design-lint/blob/master/LICENSE)

Find and fix errors in your designs for free.

---

**[⬆ Back to TOC](#table-of-contents)**

### Design Systems

#### Design Tokens

[SOURCE CODE](https://github.com/lukasoppermann/design-tokens) · [PLUGIN](https://www.figma.com/community/plugin/888356646278934516/design-tokens) · [MIT](https://github.com/lukasoppermann/design-tokens/blob/main/LICENSE)

Design Tokens is a Figma Plugin that allows you export design tokens into a json format, allowing you to transform them to different languages and platforms for web, iOS, and Android.

---

#### Styler

[SOURCE CODE](https://github.com/andrei-inc/Styler) · [PLUGIN](https://www.figma.com/community/plugin/820660579767995949/Styler) · [MIT](https://github.com/andreincu/Styler/blob/master/LICENSE)

Styler is a Figma plugin that provides a more efficient way to build and maintain design systems.

---

#### Themer

[SOURCE CODE](https://github.com/thomas-lowry/themer) · [PLUGIN](https://www.figma.com/c/plugin/731176732337510831/Themer) · [MIT](https://github.com/thomas-lowry/themer/blob/master/LICENSE)

A Figma plugin designed to allow you to swap between styles named the same from different published libraries.

---

#### Tokens Studio for Figma

[SOURCE CODE](https://github.com/six7/figma-tokens) · [PLUGIN](https://www.figma.com/community/plugin/843461159747178978/Figma-Tokens) · [MIT](https://github.com/tokens-studio/figma-plugin/blob/main/LICENSE.md)

Tokens Studio for Figma is a plugin for Figma allowing you to define and use design tokens in Figma. You can store your design tokens in JSON, sync them with a sync provider such as GitHub and define tokens even for properties that have no native support yet in Figma, such as borderRadius or spacing.

---

**[⬆ Back to TOC](#table-of-contents)**

### Developer Tools

#### Figma to Boostrap 5 Plugin

[SOURCE CODE](https://github.com/gabrielrbarbosa/figma-to-bootstrap-plugin) · [PLUGIN](https://www.figma.com/community/plugin/1287660587112027215/figma-to-bootstrap-5-plugin) · [GPLv3](https://github.com/gabrielrbarbosa/figma-to-bootstrap-plugin/blob/main/LICENSE)

Turn your Figma designs into Bootstrap 5 snippets! It generates bootstrap 5 grid, borders and utilities.

---

#### Figma Tailwindcss

[SOURCE CODE](https://github.com/jan-dh/figma-tailwindcss) · [PLUGIN](https://www.figma.com/c/plugin/785619431629077634/Figma-Tailwindcss) · NO LICENSE

Figma Tailwindcss lets you export aspects of a design made in Figma to a javascript theme file that can easily be used with Tailwindcss.

---

#### Kaleidocode

[SOURCE CODE](https://github.com/kaleidocode-app/kaleidocode) · [PLUGIN](https://www.figma.com/c/plugin/736060893363678891/Kaleidocode) · NO LICENSE

Convert VS Code themes to Figma color libraries, create new themes via JSON, and swap themes automatically.

---

#### Tailwind CSS

[SOURCE CODE](https://github.com/impulse/tailwindcss-figma-plugin) · [PLUGIN](https://www.figma.com/community/plugin/738806869514947558/Tailwind-CSS) · [MIT](https://github.com/ecklf/tailwindcss-figma-plugin/blob/main/LICENSE)

Generate styles and other cool stuff straight out of your tailwind config file.

---

**[⬆ Back to TOC](#table-of-contents)**

### Export

#### Android Resources Export

[SOURCE CODE](https://github.com/Ashung/android-resources-export-figma) · [PLUGIN](https://www.figma.com/c/plugin/735452896889481850/Android-Resources-Export) · [MIT](https://github.com/Ashung/android-resources-export-figma/blob/master/LICENSE.md)

Export multiple sizes PNG from selected slice or exportable layer, with a fixed folder structure (drawable-xhdpi, etc..) and valid name.

---

#### Figma Export

[SOURCE CODE](https://github.com/brianlovin/figma-export-zip) · [PLUGIN](https://www.figma.com/c/plugin/747228167548695118/Export-.zip) · NO LICENSE

Easily export assets from Figma directly into a .zip file.

---

#### Image Minifire

[SOURCE CODE](https://github.com/zendyani/figma-image-compression) · [PLUGIN](https://www.figma.com/community/plugin/1284557222547216612/image-minifire) · [MIT](https://github.com/zendyani/figma-image-compression/blob/main/LICENSE)

Image Minifire allows the user to compress and export images of a selected frame in Figma.

---

#### Lazy Export

[SOURCE CODE](https://github.com/kocheck/Lazy-Export) · [PLUGIN](https://www.figma.com/community/plugin/824059814042167296/Lazy-Export) · [MIT](https://github.com/kocheck/Lazy-Export/blob/production/LICENSE)

Lazy Export allows the user to quickly apply default export settings to selected objects in Figma.

---

#### Figma Sprite Generator

[SOURCE CODE](https://github.com/omidnikrah/figma-sprite-generator) · [PLUGIN](https://www.figma.com/community/plugin/1424139256012895014/goodway-sprite) · [MIT](https://github.com/omidnikrah/figma-sprite-generator/blob/main/LICENSE)

A Figma plugin to generate sprite sheets and JSON files from selected icons.

---

**[⬆ Back to TOC](#table-of-contents)**

### Icons

#### 3dicons

[SOURCE CODE](https://github.com/realvjy/3dicons-figma) • [PLUGIN](https://www.figma.com/community/plugin/1107546399747513238) • [MIT](https://github.com/realvjy/3dicons-figma/blob/main/LICENSE)

Collection 1400+ 3dicons. You can use within Figma or Figjam files quickly. The icons can be searched and filtered by color and angle.

---

#### Feather Icons

[SOURCE CODE](https://github.com/feathericons/figma-feather) · [PLUGIN](https://www.figma.com/c/plugin/744047966581015514/Feather-Icons) · NO LICENSE

Quick access to Feather icons in Figma.

---

#### Figma Text to Icon

[SOURCE CODE](https://github.com/lichin-lin/figma-text-to-icon) • NO LICENSE

A Figma plugin that generate icon from text, built with Next.js, Tailwind, Shadcn UI, and Replicate API

---

#### Iconify

[SOURCE CODE](https://github.com/iconify/iconify-figma) • [PLUGIN](https://www.figma.com/community/plugin/735098390272716381/Iconify) • [APACHE LICENSE 2.0](https://github.com/iconify/iconify-figma/blob/main/license.txt)

Import Material Design Icons, FontAwesome, Jam Icons, EmojiOne, Twitter Emoji and many other icons (more than 100 icon sets containing over 100,000 icons) to Figma document as vector shapes.

---

**[⬆ Back to TOC](#table-of-contents)**

### Maps

#### Figma Map Maker

[SOURCE CODE](https://github.com/kawamurakazushi/figma-map-maker) · [PLUGIN](https://www.figma.com/c/plugin/731312569747199418/Map-Maker) · [MIT](https://github.com/kawamurakazushi/figma-sort-it/blob/master/LICENSE)

Figma plugin to generate map, supporting Google Maps and Mapbox.

---

#### Figmap

[SOURCE CODE](https://github.com/ergum/figmap) · [PLUGIN](https://www.figma.com/community/plugin/937760472566581732) · NO LICENSE

Fully customizable styled maps and markers for Figma

---

#### Placemark Figma Plugin

[SOURCE CODE](https://github.com/placemark/figma-plugin) · [PLUGIN](https://www.figma.com/community/plugin/1189962635826293304/Placemark) · NO LICENSE

Create maps with Figma.

---

**[⬆ Back to TOC](#table-of-contents)**

### Organization

#### Figma Format

[SOURCE CODE](https://github.com/kawamurakazushi/figma-format) · [PLUGIN](https://www.figma.com/c/plugin/732774680197470712/Figma-Format) · [MIT](https://github.com/kawamurakazushi/figma-format/blob/master/LICENSE)

Figma Format let's you format your canvas by grouping them by the names.

---

#### GridGen · Automatic Table Generator

[SOURCE CODE](https://github.com/gnawx/figma-plugins/tree/master/packages/figma-gridgen) · [PLUGIN](https://www.figma.com/c/plugin/796759972238579874/GridGen) · [MIT](https://github.com/stevahnes/figma-plugins/blob/master/LICENSE)

Utilizes built-in Figma rectangles, lines, and texts to generate tables with neatly organized layers.

---

#### Project Scaffold

[SOURCE CODE](https://github.com/tushar7d/Project-Scaffold-Figma-Plugin) · [PLUGIN](https://www.figma.com/c/plugin/747372158567878238/Project-Scaffold) · NO LICENSE

This plugin Generates a Scaffold for your Product design project in just 1 click.

---

#### Super Tidy

[SOURCE CODE](https://github.com/basiclines/figma-super-tidy) · [PLUGIN](https://www.figma.com/c/plugin/731260060173130163/Super-Tidy) · [MIT](https://github.com/basiclines/figma-super-tidy/blob/master/LICENSE)

A Figma plugin to easily align, rename and reorder your frames based in their canvas position.

---

**[⬆ Back to TOC](#table-of-contents)**

### Responsive

#### Responsify

[SOURCE CODE](https://github.com/brianlovin/figma-responsify) · [PLUGIN](https://www.figma.com/c/plugin/743654854885744527/Responsify-%E2%9A%A1%EF%B8%8F) · NO LICENSE

A Figma plugin to quickly test your designs across multiple device sizes.

---

**[⬆ Back to TOC](#table-of-contents)**

### Text

#### Better Font Picker

[SOURCE CODE](https://github.com/nitinrgupta/figma-better-font-picker) · [PLUGIN](https://www.figma.com/c/plugin/739922281164562258/Better-Font-Picker) · [MIT](https://github.com/yenargy/figma-better-font-picker/blob/develop/LICENSE)

Better Font Picker helps you select fonts with a preview of how it looks.

---

#### Content Buddy

[SOURCE CODE](https://github.com/basiclines/figma-content-buddy) · [PLUGIN](https://www.figma.com/c/plugin/731260490045684148/Content-Buddy) · [MIT](https://github.com/basiclines/figma-content-buddy/blob/master/LICENSE)

A Figma Plugin that makes replacing text content in multiple layers super easy for anyone.

---

#### Tolgee

[SOURCE CODE](https://github.com/tolgee/figma-plugin) • [PLUGIN](https://www.figma.com/community/plugin/1212381421658754793/Tolgee-localization) • [MIT](https://github.com/tolgee/figma-plugin/blob/main/LICENSE)

Easily manage translations within your Figma design files by connecting Figma with Tolgee localization platform.

---

#### Typograf

[SOURCE CODE](https://github.com/golmakov/figma-typograf-plugin) · [PLUGIN](https://www.figma.com/c/plugin/745519632050796775/Typograf) · NO LICENSE

Figma plugin for making good typographic text.

---

**[⬆ Back to TOC](#table-of-contents)**

### Utilities

#### Batch Styler

[SOURCE CODE](https://github.com/six7/figma-batch-styler) · [PLUGIN](https://www.figma.com/community/plugin/818203235789864127/Batch-Styler) · [MIT](https://github.com/six7/figma-batch-styler/blob/master/LICENSE)

Batch Styler is a plugin allowing you to edit multiple text or color styles at once.

---

#### Component to page

[SOURCE CODE](https://github.com/thomas-lowry/component-to-page) · [PLUGIN](https://www.figma.com/c/plugin/749583881837062159/Component-Page) · [MIT](https://github.com/thomas-lowry/component-to-page/blob/master/LICENSE)

This plugin enables you to create a component (like you would in Sketch) where the master moves to a dedicated page leaving an instance in place.

---

#### Edit in place

[SOURCE CODE](https://github.com/thomas-lowry/edit-in-place) · [PLUGIN](https://www.figma.com/c/plugin/754704266165393093/Edit-in-place) · NO LICENSE

Select any instance of a local component and edit the master component in place from the context of wherever you are using the instance. This is handy if your master components are on another page!

---

#### Emoji Pattern Generator

[SOURCE CODE](https://github.com/niyamax/figma-emoji-pattern-generator) • [PLUGIN](https://www.figma.com/community/plugin/1307592924492712453/emoji-pattern-generator) • [MIT](https://github.com/niyamax/figma-emoji-pattern-generator/blob/main/LICENSE)

A Figma plugin that generates beautiful patterns using emojis. Create unique designs with different pattern styles and emoji combinations.

---

#### Figma Measure

[SOURCE CODE](https://github.com/ph1p/figma-measure) · [PLUGIN](https://www.figma.com/c/plugin/739918456607459153/Figma-Measure) · [MIT](https://github.com/ph1p/figma-measure/blob/main/LICENSE)

A plugin for easy measurement of sizes. A small user interface allows you to add arrows for heights and widths.

---

#### Figma Remove.bg Plugin

[SOURCE CODE](https://github.com/aaroniker/figma-remove-bg) · [PLUGIN](https://www.figma.com/c/plugin/738992712906748191/Remove-BG) · NO LICENSE

Remove background of images with just 1-click

---

#### Figma Sort It

[SOURCE CODE](https://github.com/kawamurakazushi/figma-sort-it) · [PLUGIN](https://www.figma.com/c/plugin/731324768889901500/Sort-It) · [MIT](https://github.com/kawamurakazushi/figma-sort-it/blob/master/LICENSE)

Sort selected Frames or Layers by names or position.

---

#### Figma Walker

[SOURCE CODE](https://github.com/kawamurakazushi/figma-walker) · [PLUGIN](https://www.figma.com/c/plugin/732773762837487095/Figma-Walker) · [MIT](https://github.com/kawamurakazushi/figma-walker/blob/master/LICENSE)

Walkthrough your project without lifting your keyboard

---

#### Figmoji

[SOURCE CODE](https://github.com/nitinrgupta/figmoji) · [PLUGIN](https://www.figma.com/c/plugin/736612173445813953/Figmoji) · NO LICENSE

Add emojis seamlessly onto your designs.

---

#### Nester

[SOURCE CODE](https://github.com/thomas-lowry/nester) · [PLUGIN](https://www.figma.com/c/plugin/787337376836787569/Nester) · [MIT](https://github.com/thomas-lowry/nester/blob/master/LICENSE)

Nester will nest any object that resides above (but not inside) a top-level frame/artboard.

---

#### Pattern Hero

[SOURCE CODE](https://github.com/nitinrgupta/figma-pattern-hero) · [PLUGIN](https://www.figma.com/c/plugin/740556241021336678/Pattern-Hero) · NO LICENSE

Pattern Hero enables you to place selected elements or frames in a grid to create patterns.

---

#### Randomiser

[SOURCE CODE](https://github.com/niyamax/Figma-Randomiser) • [PLUGIN](https://www.figma.com/community/plugin/1189284785668093844/randomiser) • [CC0-1.0](https://github.com/niyamax/Figma-Randomiser/blob/main/LICENSE)

A Figma plugin which helps the users to randomise the size, position and color of the elements with in a frame

---

#### Reattach Instance

[SOURCE CODE](https://github.com/renancamm/figma-reattache-instance) · [PLUGIN](https://www.figma.com/c/plugin/741415678427267506/Reattach-Instance) · [MIT](https://github.com/renancamm/figma-reattache-instance/blob/master/LICENSE)

Relink a frame to a component by searching for similar instances.

---

#### Reverse layer order

[SOURCE CODE](https://github.com/mikegowen/figma-reverse-layer-order) · [PLUGIN](https://www.figma.com/c/plugin/738853407874474111/Reverse-Layer-Order) · NO LICENSE

Figma plugin to reverse the order of the selected layers.

---

#### Send to top

[SOURCE CODE](https://github.com/thomas-lowry/send-to-top) · [PLUGIN](https://www.figma.com/community/plugin/740593880490123393) · [MIT](https://github.com/thomas-lowry/send-to-top/blob/master/LICENSE)

Sends selected layers to the very top of the layer stack above all other frames on the canvas.

---

#### Sorter

[SOURCE CODE](https://github.com/thomas-lowry/sorter) · [PLUGIN](https://www.figma.com/c/plugin/742038190980789811/Sorter) · [MIT](https://github.com/thomas-lowry/sorter/blob/master/LICENSE)

Enables the user to quickly sort the order of layers based on position, name (alphabetical), reverse order, or random.

---

#### Variables Import

[SOURCE CODE](https://github.com/microsoft/figma-variables-import) • [PLUGIN](https://www.figma.com/community/plugin/1253424530216967528/variables-import) • [MIT](https://github.com/microsoft/figma-variables-import/blob/main/LICENSE.txt)

The plugin allows import of design token as Figma variables. Note the parser is not fully compliant and does not support every token in the DTCG format.

---

**[⬆ Back to TOC](#table-of-contents)**

### Misc

#### Retro Snake

[SOURCE CODE](https://github.com/gnawx/figma-plugins/tree/master/packages/figma-retro-snake) · [PLUGIN](https://www.figma.com/community/plugin/812994090875519300/Retro-Snake) · [MIT](https://github.com/stevahnes/figma-plugins/blob/master/LICENSE)

Bringing the retro game we all love into Figma, Snake!

---
