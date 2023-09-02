## Environment

### Install LaTex on your System

[TexLive Quick Install](https://www.tug.org/texlive/quickinstall.html)  

#### Other install options:  
**Ubuntu**

[texlive packages](https://packages.ubuntu.com/search?keywords=texlive)  
[latexmk packages](https://packages.ubuntu.com/search?keywords=latexmk)
```sh
apt install texlive texlive-fonts-extra latexmk
```

**MacOS**
```sh
# macOS MacTex Install
brew --cask install mactex-no-gui

# Updating the packages
sudo tlmgr update --self && sudo tlmgr update --all
```

### VS Code
[LaTeX Workshop Extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)

## Compile
1\. Using terminal  
```sh
latexmk resume.tex
```
2\. Using VS Code  
`VS Code` -> `Build LaTex project`