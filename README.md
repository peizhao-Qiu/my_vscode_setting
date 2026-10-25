# VS Code settings backup

This repository contains the portable parts of my VS Code configuration:

- `settings.json` — editor and VSCodeVim settings
- `keybindings.json` — user keyboard shortcuts
- `extensions.json` — recommended extensions

## Restore

Copy `settings.json` and `keybindings.json` into:

`%APPDATA%\Code\User\`

Open a folder containing `.vscode/extensions.json`, or install the extension IDs
listed in `extensions.json`, to restore the recommended extensions.

Authentication, logs, caches, machine-specific state, and extension data are
intentionally excluded.
