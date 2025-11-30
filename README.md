# Upenai Theme

Dark and Light themes optimized for tutorial videos, works across Cursor, VSCode, and other VSCode-like editors forks.


## Build

```bash
npx @vscode/vsce package --out dist/
```

## Install

### VS Code
```bash
code --install-extension dist/upenai-theme-*.vsix
```

### Cursor
```bash
cursor --install-extension dist/upenai-theme-*.vsix
```

Or manually: Open Command Palette → `Extensions: Install from VSIX` → Select the `.vsix` file from the `dist/` folder


