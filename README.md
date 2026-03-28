# vscode-context

Visual Studio Code has a [known bug](https://github.com/microsoft/vscode/issues/260389) where some of its Windows context options are missing. vscode-context fixes that.

To use this, download `vscode-context.reg`, replace `<YOUR_USER>` with your Windows username, and import it into the Windows Registry Editor. If VS Code is installed somewhere other than the default path, update that path too.

This registry file supports:
- Files
- Right clicking ON folders
- Right clicking INSIDE folders

## License
MIT, do whatever you want. Not our fault if something breaks.
