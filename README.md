# CV

My CV (resume) based on LaTeX template by Timmy Chan.

## Install LaTeX

[TexLive Quick Install](https://www.tug.org/texlive/quickinstall.html)

### Fedora

```sh
sudo dnf install texlive-scheme-basic texlive-sourcesanspro texlive-moresize texlive-ly1 texlive-anyfontsize texlive-standalone texlive-import texlive-blindtext latexmk
```

### MacOS

```sh
# macOS MacTex Install
brew --cask install mactex-no-gui

# Updating the packages
sudo tlmgr update --self && sudo tlmgr update --all
```

## Compile

### In terminal  

```sh
latexmk -pdf -output-directory="build" resume.tex
```

### In VS Code

Install [LaTeX Workshop Extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop), then `VS Code` -> `Build LaTex project`.
