# Hello World Example

This example uses esbuild+typescript for VSCode extension development.

## Getting Started

```bash
npm i
npm run build
```

Press `F5` key to start debbuging extension.

To watch code change execute below.

```bash
npm run watch
```

Then press `Ctrl+R` (reload window) to apply code change.

## VS Code API

### `vscode` module

- [`commands.registerCommand`](https://code.visualstudio.com/api/references/vscode-api#commands.registerCommand)
- [`window.showInformationMessage`](https://code.visualstudio.com/api/references/vscode-api#window.showInformationMessage)

### Contribution Points

- [`contributes.commands`](https://code.visualstudio.com/api/references/contribution-points#contributes.commands)

## Publishing to marketplace

See [Publishing Extensions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension).
