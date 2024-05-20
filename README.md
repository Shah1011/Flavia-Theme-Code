<p align="center">
  <img alt="Flavia Logo" src="/images/logo.png" width="100" />
</p>
<h1 align="center">
  Flavia Theme for VS Code
</h1>
<p align="center">
  A minimalistic dark theme for <a href="https://flavia-theme.vercel.app/">VS Code and Sublime Text editors</a>.
</p>


![demo](/images/demo.png)

## Installation via VS Code

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Flavia`
3. Click **Install** to install it
4. Click **Reload** to reload the editor
5. Code > Preferences > Color Theme > **Flavia**

## Manual Installation

Read the [VSC Extension Quickstart Guide](https://github.com/DanishQ1011/Flavia-Dark-Theme/blob/main/vsc-extension-quickstart.md)

## Icon Theme

The file icon theme seen in the screenshot above is [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) with these settings:

```json
  "material-icon-theme.folders.color": "#8695b7",
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.hidesExplorerArrows": true,
```

## Color Reference

### Syntax Colors

|                               Color                                | Usage                                           |
| :----------------------------------------------------------------: | ----------------------------------------------- |
| ![#ffa7a6](https://via.placeholder.com/10/ffa7a6.png?text=+) `#ffa7a6` | Variables, properties          |
| ![#6ff254](https://via.placeholder.com/10/6ff254.png?text=+) `#6ff254` | Keywords         |
| ![#aa2fbc](https://via.placeholder.com/10/aa2fbc.png?text=+) `#aa2fbc` | Numbers                            |
| ![#ff00a7](https://via.placeholder.com/10/ff00a7.png?text=+) `#ff00a7` | Classes, constants                      |
| ![#009bdb](https://via.placeholder.com/10/009bdb.png?text=+) `#009bdb` | Function, methods |
| ![#ffdf35](https://via.placeholder.com/10/ffdf35.png?text=+) `#ffdf35` | Strings                 |
| ![#00776c](https://via.placeholder.com/10/00776c.png?text=+) `#00776c` | Operators, special functions                 |

### UI Colors

|                               Color                                | Usage                                      |
| :----------------------------------------------------------------: | ------------------------------------------ |
| ![#1b1b27](https://via.placeholder.com/10/1b1b27.png?text=+) `#1b1b27` | Editor background                          |
| ![#101019](https://via.placeholder.com/10/101019.png?text=+) `#101019` | Highlight, widgets, panels                 |
| ![#6679a4](https://via.placeholder.com/10/6679a4.png?text=+) `#6679a4` | Dividers, subtle UI elements               |
| ![#28b95c](https://via.placeholder.com/10/28b95c.png?text=+) `#28b95c` | Status bar text, buttons, etc              |
| ![#d7dce2](https://via.placeholder.com/10/d7dce2.png?text=+) `#d7dce2` | Active text, anything that should be white |
| ![#ffcc66](https://via.placeholder.com/10/ffcc66.png?text=+) `#ffcc66` | Accent, list tree titles, badges, etc      |
| ![#bae67e](https://via.placeholder.com/10/bae67e.png?text=+) `#bae67e` | Addition highlights                        |
| ![#ef6b73](https://via.placeholder.com/10/ef6b73.png?text=+) `#ef6b73` | Deletion highlights, errors, warnings      |
| ![#5ccfe6](https://via.placeholder.com/10/5ccfe6.png?text=+) `#5ccfe6` | Modified highlights                        |

## Theming Reference

[VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)

[VS Code Theme Documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

[VS Code Publishing Extensions](https://code.visualstudio.com/docs/extensions/publish-extension)

```bash
vsce publish patch/minor/major
```
