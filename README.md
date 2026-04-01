# Obsidian Minimal Polish Theme Snippets

A collection of highly refined, polished CSS snippets for Obsidian that create a beautiful, modern, and interactive reading and editing experience. Available in both Light and Dark mode variants.

## ✨ Features

- **Modern Typography:** Clean headings with custom gradient underlines, tailored font stacks, and responsive alignments.
- **Interactive Image Gallery:** Images and Mermaid diagrams seamlessly enlarge and cast deep shadows when you hover over them, acting like a built-in magnifier without needing any external plugins.
- **High-Contrast Syntax Highlighting:** Explicitly styled target classes for both Reading Mode (PrismJS) and Live Preview (CodeMirror 6), ensuring code blocks are always incredibly readable, mimicking GitHub's beautiful syntax colors.
- **Custom Tables:** Beautiful table layouts that scroll horizontally, feature custom hover states, and prevent UI-breaking overflow.
- **Themed Callouts & Blockquotes:** Upgraded standard Obsidian callouts and blockquotes with elegant transition animations, gradient borders, and crisp box-shadows.
- **Enhanced File Explorer:** Deep opacity fading for standard folders to reduce visual clutter, custom colored icons for specific folders (e.g., `Cyber Security`, `Information Technology`), and slick hover translation animations.
- **Dynamic Checkboxes & Tags:** Modern pill-shaped interactive tags and custom animated checkboxes.

## 📦 Installation

1. Download the `Minimal.css` (Light Theme) and/or `Minimal-Dark.css` (Dark Theme) files.
2. Open your Obsidian Vault.
3. Go to **Settings** > **Appearance** > **CSS Snippets**.
4. Click the folder icon to open the snippets folder (`.obsidian/snippets`).
5. Place the downloaded `.css` files into this folder.
6. Return to Obsidian and toggle the snippet(s) **ON** in the Appearance menu.

> [!TIP]
> You can safely enable both snippets. If you want full control, keep the Light snippet active when using the light theme, and toggle the Dark snippet when switching to Obsidian's dark mode.

## 🎨 File Explorer Customization

You can easily add your own colored folders in the sidebar tree by editing the following section in the CSS files:

```css
.nav-folder:has(> .nav-folder-title[data-path="Your Folder Name"]) {
  --tree-color: #YOURCOLOR;
}
```

## 📸 Screenshots

*(Replace these placeholders with actual screenshots of your vault!)*

| Light Theme | Dark Theme |
| :---: | :---: |
| `<img src="docs/light-preview.png" width="400"/>` | `<img src="docs/dark-preview.png" width="400"/>` |

## 🛠️ Modifying Syntax Highlighting 

If you wish to change the code block colors, look for the `SYNTAX HIGHLIGHTING` section at the bottom of the snippet files. The snippet uses raw `.token` and `span.cm-*` classes to **guarantee** the colors apply and bypass any messy plugin conflicts.

## 📝 License

This project is open-source. Feel free to fork, modify, and use it in your own Obsidian setups.
