# Overview
<a href="https://marketplace.visualstudio.com/items?itemName=tpill90.latex-Utilities-fork">
<img alt="version" src="https://vsmarketplacebadges.dev/version-short/tpill90.latex-utilities.png?style=flat-square&color=579983&logo=visual-studio-code&logoColor=C6EDE2"/></a>
</br>
</br>

Temporary fork of [tpill90/LaTeX-Utilities](https://github.com/tpill90/LaTeX-Utilities) until [tpill90/LaTeX-Utilities/pull/408](https://github.com/tpill90/LaTeX-Utilities/pull/408) is merged and published.

# Install

An add-on to the vscode extension [LaTeX Utilities](https://marketplace.visualstudio.com/items?itemName=tpill90.latex-Utilities-fork)

# How to Build

```bash
# If not already installed
npm install -g @vscode/vsce

# Do the actual publish
npm install
vsce package --no-yarn
vsce publish
```