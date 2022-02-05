# Nomad Pack Flavor Go Template Syntax Highlight Support for VSCode

[![Launched](https://img.shields.io/badge/VSCode--Go--Template-launched-brightgreen.svg?logo=visual-studio-code)](https://github.com/RickyGrassmuck/vscode-nomad-pack-go-template)
[![GitHub license](https://img.shields.io/github/license/RickyGrassmuck/vscode-nomad-pack-go-template.svg)](https://raw.githubusercontent.com/RickyGrassmuck/vscode-nomad-pack-go-template/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/RickyGrassmuck/vscode-nomad-pack-go-template.svg)](https://github.com/RickyGrassmuck/vscode-nomad-pack-go-template/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/RickyGrassmuck/vscode-nomad-pack-go-template.svg)](https://github.com/RickyGrassmuck/vscode-nomad-pack-go-template/network)
[![GitHub issues](https://img.shields.io/github/issues/RickyGrassmuck/vscode-nomad-pack-go-template.svg)](https://github.com/RickyGrassmuck/vscode-nomad-pack-go-template/issues)
[![Coverage Status](https://coveralls.io/repos/github/RickyGrassmuck/vscode-nomad-pack-go-template/badge.svg?branch=master)](https://coveralls.io/github/RickyGrassmuck/vscode-nomad-pack-go-template?branch=main)

Nomad Pack Flavor Go Template Syntax Highlight Support for VSCode.

**Forked from https://github.com/jinliming2/vscode-go-template**

## Release

- **[Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=RickyGrassmuck.vscode-nomad-pack-go-template) / Recommend**
- [GitHub Release](https://github.com/RickyGrassmuck/vscode-nomad-pack-go-template/releases)

## Features

- Support syntax highlighting for Go Template embedded in literal string in Go source file.

  ![Go](./assets/screenshots/go.png)

- Support syntax highlighting for Go Template files: `*.go.txt`, `*.go.tpl`, `*.go.tmpl`, `*.gtpl`.

  ![Template](./assets/screenshots/tpl.png)

- Support syntax highlighting for Go Template embedded in Markdown.

  ![Markdown](./assets/screenshots/markdown.png)

- Support syntax highlighting for Go Template embedded in `HTML`, `JS`, and `CSS` files.

  ![HTML](./assets/screenshots/html.png)

- Support syntax highlighting for Go Template embedded in unknown extension files which begin with Go Template Comment. Ex: `{{ /* Go Template */ }}`.

  ![Comment](./assets/screenshots/comment.png)

- Support syntax highlighting for any other custom specified file extensions.

  ![Custom](./assets/screenshots/custom.png)

## Known Issues

1. This extension cannot bypass grammar check error from Language Server.
1. Template syntax highlighting in some languages may need to reload extension. (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> `go-template.reload`)

## Release Notes

[Changelog](./CHANGELOG.md)
