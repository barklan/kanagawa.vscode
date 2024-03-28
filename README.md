<p align="center">
  <h2 align="center">🌊 KANAGAWA.vscode 🌊</h2>
  <p align="center">
      <a href="https://marketplace.visualstudio.com/items?itemName=qufiwefefwoyn.kanagawa">
        <img src="https://vsmarketplacebadge.apphb.com/version/qufiwefefwoyn.kanagawa.svg" />
      </a>
      <a href="https://marketplace.visualstudio.com/items?itemName=qufiwefefwoyn.kanagawa">
        <img src="https://img.shields.io/visual-studio-marketplace/i/qufiwefefwoyn.kanagawa" />
      </a>
      <a href="https://marketplace.visualstudio.com/items?itemName=qufiwefefwoyn.kanagawa">
        <img src="https://vsmarketplacebadge.apphb.com/rating-star/qufiwefefwoyn.kanagawa.svg" />
      </a>
  </p>
</p>

<p align="center">
  <img src="assets/main.png" width="600" >
</p>

<br>

<p align="center">
VS Code port of amazing <a href="https://github.com/rebelot/kanagawa.nvim">KANAGAWA.nvim</a> colorscheme by rebelot.
Credit for initial port goes to <a href="https://github.com/conner-calhoun">conner-calhoun</a>.
</p>

<p align="center">
  <h2 align="center"><img src="assets/screenshot.png"></h2>
</p>

## Semantic tokens

Theme supports and recommends enabling semantic tokens.

### TypeScript

Enabled by default.

### Go

```json
{
  "gopls": { "ui.semanticTokens": true }
}
```

#### rust-analyzer

```json
{
  "rust-analyzer.highlighting.strings": true
}
```

#### `C#`

```json
{
  "csharp.semanticHighlighting.enabled": true
}
```

## Customization

### Comments

If you prefer comments to stand out in your code - this looks nice:

```json
{
  "editor.tokenColorCustomizations": {
    "[Kanagawa]": {
      "comments": {
        "foreground": "#FF9E3B"
      }
    }
  }
}
```

Paste it in your `settings.json`.

## Misc

You can find this theme's colors for different terminal emulators [here](https://github.com/rebelot/kanagawa.nvim#extras).
If you like this theme, consider supporting [original author](https://github.com/rebelot/kanagawa.nvim#donate).
