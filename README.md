# visual-studio-code
Tips &amp; Tricks for Visual Studio Code (VSCode) on MacOS

## Basic keyboard shortcuts
Views:
- `⌘-⇧-e`: folder view
- `⌘-⇧-f`: search view
- `⌘-⇧-x`: extensions view
- `⌃-⇧-g`: git view

Other:
- `⌘-⇧-p`: command palette (`F1`)
  - Supports camel case search: `RSTIAT` will find "`Run Selected Text In Active Terminal`" 
- `⌘-k z`: zen mode
- `⌃-⌘-f`: full screen
- `⌘-⇧-v`: preview (Markdown only?)
- [Cheat sheet](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)

## Installing the 'code' command
Type 'shell' in the command palette and choose `Install 'code' command in PATH`. You can now open VSCode from a terminal:
```
$ code <path>
```

## Editing
- `⌘-c`: copy (works on entire line if nothing selected)
- `⌘-v`: paste (works on entire line if nothing selected)
- `⌘-x`: cut (works on entire line if nothing selected)
- `⌘-]`: indent selection (unindent: ⌘-[)
- `⌘-L`: expand line selection
- `⌥-up/down`: move selection up/down

## Terminal
- `⌃-\``: Open terminal
- `⌘-k`: clear terminal

You can select part of a bash script in an editor, you can choose `` in the command palette

## Preferences
- `⌘-,`: preferences
- `⌘-k-s`: keyboard shortcuts

In the command palette choose `CLSS` (`C`onfigure `L`anguage `S`pecific `S`ettings) and choose (for instance) Python from the dropdown.

## Extensions

- `⌘-⇧-x` or go to [vscode market place](https://marketplace.visualstudio.com/vscode)

Recommended extensions:
* `snippets` (html snippets, node snippets, python snippets, ..) add snippets to autocompletion
* [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify) adds 'Beautify' to the command palette
* [Express](https://marketplace.visualstudio.com/items?itemName=Compulim.vscode-express) adds 'Express' to the command palette, to host your workspace (static files)
* [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) 
  - Create a new file with extension *.http
  - Add commands in this file, like `GET https://www.google.com/search?q=marsmannetjes`
  - Click the '`Send Request`' link above it
