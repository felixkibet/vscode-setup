# VS Code Extensions List

This repository contains a list of all Visual Studio Code extensions I use. The `vscode-extensions.txt` file can be used to quickly set up the same extensions on a new installation of VS Code.

## Contents

- `vscode-extensions.txt`: A list of VS Code extensions currently installed.

## Exporting Extensions

To generate a list of all installed extensions, use the following command in your terminal:

```bash
code --list-extensions > vscode-extensions.txt
```
## Clone this repository (or download vscode-extensions.txt directly)
```
git clone https://github.com/felixkibet/vscode-setup.git
cd vscode-setup
```

## Run the following command to install each extension listed in vscode-extensions.txt
```
cat vscode-extensions.txt | xargs -n 1 code --install-extension
```
