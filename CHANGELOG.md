# Change Log

## [0.1.0] - 2022-02-04

Initial release after forking from https://github.com/jinliming2/vscode-go-template. All credit to them,
I just made a few changes to support the different opening and closing delimiters used in Nomad-Pack templates.
### Added

- Markdown support: go-template
- Refactor: use semantic API
- Support config for matching file extension / language id (implement using semantic API)
- Support syntax highlighting for Go Template embedded in literal string in Go source file.
- Support syntax highlighting for Go Template files: `*.gtpl`.
- Support syntax highlighting for Go Template files: `*.go.txt`, `*.go.tpl`, `*.go.tmpl`.
- Support syntax highlighting for Go Template embedded in `HTML`, `JS`, and `CSS` files.
- Support syntax highlighting for Go Template embedded in unknown extension files which begin with `{{ /* Go Template */ }}`.
