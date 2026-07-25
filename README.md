# vscode-extension-pack

My personal Visual Studio Code extension pack with my favorite extensions.

## Installation

Download the `.vsix` file:

```bash
git clone https://github.com/glevine/vscode-extension-pack.git
cd vscode-extension-pack
code --install-extension vscode-extension-pack-0.0.0.vsix
```

Or download it directly from the repo and run:

```bash
code --install-extension vscode-extension-pack-0.0.0.vsix
```

You can also install it using the VS Code UI:

1. Open Extensions panel (`Cmd+Shift+X`)
2. Click the `...` menu -> `Install from VSIX...`
3. Select the downloaded `.vsix` file

## Development

### Prerequisites

- [mise](https://mise.jdx.dev)
- git

### Setup

```bash
git clone https://github.com/glevine/vscode-extension-pack.git
cd vscode-extension-pack
mise install
npm install
```

### Adding/Removing Extensions

Edit the `extensionPack` array in `package.json` with the extension IDs you want.

### Building the Pack

```bash
npm run package
```

This generates `vscode-extension-pack-0.0.0.vsix`

Don't forget to reinstall.

## License

MIT
