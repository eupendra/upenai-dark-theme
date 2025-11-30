# Upenai Dark Theme

## Build

```bash
npx @vscode/vsce package
```

This creates a `.vsix` file in the root directory.

## Install

### VS Code
```bash
code --install-extension dist/upenai-dark-theme-0.1.0.vsix
```

### Cursor
```bash
cursor --install-extension dist/upenai-dark-theme-0.1.0.vsix
```

Or manually: Open Command Palette → `Extensions: Install from VSIX` → Select the `.vsix` file from the `dist/` folder


