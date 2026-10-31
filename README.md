<p align="center">
  <img src="assets/screenshots/large_interface.png" alt="Matte logo" width="1080" />
</p>


<p align="center">
  <img src="assets/logo.png" alt="Matte logo" width="112" />
</p>

<h1 align="center">Matte Minimal</h1>

<p align="center">
  <strong >One extension. Multiple editor aesthetics.</strong><br />
  Pure Black. Perfect Contrast. Premium Themes for VS Code.
  <br/>Pitch-black OLED, refined dark and light themes inspired by Cursor, Vercel, VS Code, and Xcode.
</p>



<!-- After the extension is published, you can add official Marketplace badges here. Avoid hard-coded download counts or version numbers. -->

Matte brings several visual styles together in one extension, so you can switch between them without installing a separate theme extension for every look. Choose a deep dark workspace, a true-black OLED variant, or a clean light palette from the same theme picker.

> **Independent project:** Matte is not affiliated with, sponsored by, or endorsed by Cursor, Vercel, Microsoft, Apple, or their respective products. Their names are used only to identify the design inspirations or theme variants. See [Third-party notices](THIRD_PARTY_NOTICES.md).

## Why Matte?

- **One install, many styles.** Keep the theme families you like in one extension.
- **OLED-focused options.** Selected variants use a pitch-black `#000000` workspace background, with complementary UI colors chosen for separation and readability.
- **Dark and light choices.** Switch visual styles without managing several separate theme extensions.
- **A consistent theme picker.** Find variants by searching for terms such as `OLED`, `Cursor`, `Vercel`, `VS Code`, or `Xcode`.
- **Theme-only.** Matte provides color themes; it does not need to run a background service or collect your project data.

Color appearance and contrast depend on the selected theme, editor, display, and user settings. OLED-black backgrounds do not guarantee lower eye strain or accessibility for every user.

## Theme collection

Matte currently defines **20 themes across four visual families**. Names below describe the collection; the exact visible labels are defined in `package.json`.

### Cursor-inspired themes

| Theme | Style |
| --- | --- |
| Cursor OLED | Pitch-black OLED variant |
| Cursor Dark | Classic dark palette |
| Cursor Dark Midnight | Deeper midnight dark palette |
| Cursor Dark High Contrast | High-contrast dark variant |
| Cursor Dark Colorblind | Alternate dark color variant |
| Cursor Light | Light palette |
| Cursor Light High Contrast | High-contrast light variant |
| Cursor Light Colorblind | Alternate light color variant |

<table>
  <tr>
    <td align="center">
      <img src="_gemini/img/image.png" width="600" /><br />
      <b>Variant One</b>
    </td>
    <td align="center">
      <img src="_gemini/img/image.png" width="600" /><br />
      <b>Variant Two</b>
    </td>
    <td align="center">
      <img src="_gemini/img/image.png" width="600" />
      <br />
      <b>Variant Three</b>
    </td>
  </tr>
</table>
### Vercel-inspired themes

| Theme | Style |
| --- | --- |
| Vercel Dark | Minimal dark palette with OLED-oriented black surfaces |
| Vercel Light | Minimal light palette |

### VS Code-inspired themes

| Theme | Style |
| --- | --- |
| VS Code OLED | VS Code-inspired palette adapted for a pitch-black workspace |

### Xcode-inspired themes

| Theme | Style |
| --- | --- |
| Xcode Classic Dark | Classic dark palette |
| Xcode Dark OLED | Dark palette adapted for pitch-black surfaces |
| Xcode Classic Light | Classic light palette |
| Xcode Default Dark | Default-style dark palette |
| Xcode Default Dark (Modified) | Modified dark variant |
| Xcode Civic Dark | Civic dark palette |
| Xcode Midnight Dark | Midnight dark palette |
| Xcode Low Key Light | Low-key light palette |
| Xcode Spartan Light | Minimal light palette |

Names that refer to other products describe visual inspiration or a palette family, not official endorsement. Availability and rendering can vary across compatible editors.

<!--
PRE-PUBLISH SCREENSHOT GALLERY
Capture real screenshots, save them in assets/screenshots/, and then uncomment this section.

## Preview

<p align="center">
  <img src="assets/screenshots/Matte-cursor-oled.png" alt="Matte Cursor OLED theme in a code editor" width="900" />
</p>
<p align="center">
  <img src="assets/screenshots/Matte-vercel-dark.png" alt="Matte Vercel Dark theme in a code editor" width="900" />
</p>
<p align="center">
  <img src="assets/screenshots/Matte-vscode-oled.png" alt="Matte VS Code OLED theme in a code editor" width="900" />
</p>
<p align="center">
  <img src="assets/screenshots/Matte-xcode-dark.png" alt="Matte Xcode-inspired dark theme in a code editor" width="900" />
</p>
-->

## Installation

### Visual Studio Code

After Matte is published to the Visual Studio Marketplace, install it from the Extensions view:

1. Open the Extensions view with `Ctrl+Shift+X` on Windows/Linux or `Cmd+Shift+X` on macOS.
2. Search for **Matte Minimal**.
3. Select the extension published by `Yuvraj Rastogi`, then choose **Install**.

You can also install it from a terminal after publication:

```bash
ext install YuvrajRastogi.Matte
```

### Cursor and other VS Code-compatible editors

Extension-registry support differs by editor. Search for Matte in the editor's configured registry. If it is not listed, check whether that editor supports Open VSX or installing a `.vsix` file manually. Compatibility is not guaranteed merely because an editor is based on VS Code.

## Apply a theme

1. Open the theme picker with `Ctrl+K Ctrl+T` on Windows/Linux or `Cmd+K Cmd+T` on macOS.
2. Search for `OLED`, `Cursor`, `Vercel`, `VS Code`, or `Xcode`.
3. Preview a theme, then press `Enter` to apply it.

You can return to the same picker at any time to switch themes. Theme labels may be updated between releases; use the names displayed by your installed version.

## Compatibility

Matte uses the standard VS Code color-theme contribution format. It is intended for Visual Studio Code and compatible editors that support these theme contributions. Individual editors may render UI colors differently or omit some theme color keys. Test your preferred theme in your own editor and version.

This project does not claim compatibility with every VS Code-derived editor or every web/remote environment.

## Feedback and contributions

Found a missing color, unreadable token, or editor-specific rendering issue? Use the repository’s Issues link in the extension’s Resources panel and include:

- The exact Matte theme name.
- The editor and version you use.
- The language or UI area affected.
- A screenshot, if it helps explain the issue.

Please do not include passwords, tokens, private source code, or other sensitive information in screenshots or issue reports.

Contribution proposals are welcome, but please open an issue first for substantial palette changes. Do not submit theme files or assets copied from another project unless their license permits the proposed use and the source is documented.

### Credits and Trademarks

> Matte is an independent project. It is not affiliated with, sponsored by, or endorsed by Cursor, Vercel, Visual Studio Code, Xcode, or their respective owners. Certain color palettes and design choices in Matte are inspired by the visual styles of those products. All product names, logos, and trademarks mentioned here belong to their respective owners and are used for identification only.

> Giving credit to a source does not grant any right to use or redistribute it. Where third-party material is included in or adapted for this project, its origin, license terms, and any required notices are recorded in THIRD_PARTY_NOTICES.md. Such material remains subject to its own license.

### License

> The original Matte materials are licensed under the Matte Custom Use and Redistribution License. This is a custom license and is not an open source license as defined by the Open Source Initiative (OSI). Third-party materials remain governed by their own terms. Please read the LICENSE file and THIRD_PARTY_NOTICES.md before using or redistributing this project.

The full terms are set out in the LICENSE file.
