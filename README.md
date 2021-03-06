# Code navigator for typescript

[![Visual Studio Marketplace](https://img.shields.io/vscode-marketplace/v/kdcro101.typescript-code-navigator.svg)](https://marketplace.visualstudio.com/items?itemName=kdcro101.typescript-code-navigator)
[![Installs](https://img.shields.io/vscode-marketplace/d/kdcro101.typescript-code-navigator.svg)](https://marketplace.visualstudio.com/items?itemName=kdcro101.typescript-code-navigator)
[![Rating](https://img.shields.io/vscode-marketplace/r/kdcro101.typescript-code-navigator.svg)](https://marketplace.visualstudio.com/items?itemName=kdcro101.typescript-code-navigator)

Extension provides ability to browse typescript source code by using side panel populated with list of declarations in currently opened typescript file.

![](https://raw.githubusercontent.com/kdcro101/vscode-typescript-code-navigator/master/preview/preview.gif)

## Install

Open Visual Studio Code press CTRL+p and type or copy and paste:

`ext install kdcro101.typescript-code-navigator`

## Usage

To open panel press CTRL+P (Show all commands) and select `Show code navigator for typescript`

    
## Configuration
`typescript.navigator.collapseEnums` : `boolean`
 - should collapse enum declarations when populating panel, `default = true`

`typescript.navigator.collapseInterfaces` : `boolean`
- should collapse interface declarations when populating panel, `default = true`

`typescript.navigator.collapseClasses` : `boolean`
- should collapse class declarations when populating panel, `default = false`

`typescript.navigator.showVisibilityLabels` : `boolean`
- show class member modifiers (visibility) in navigator, `default = true` 

`typescript.navigator.showIcons` : `boolean`
- show icons in navigator, `default = true` 

`typescript.navigator.showDataTypes` : `boolean`
- show data types in navigator (if available), `default = true` 
                                           


## LICENSE

[GPL v3 License](https://raw.githubusercontent.com/kdcro101/vscode-typescript-code-navigator/master/LICENSE)
