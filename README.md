#Alchemy
![Seven Metals of the Ancients](/examples/SevenMetals.png)

This LaTeX package is meant to provide (Tikz) drawings of alchemical symbols.

##Installation
I hope to have this package in CTAN as soon as possible. Stay tuned.

#Linux
Clone this repository to `~/texmf/tex/`:
```bash
mkdir ~/texmf/tex
cd ~/texmf/tex
git clone https://github.com/michaelplews/alchemy-latex.git
```

#OSX (Mac)
Create the folder ~/Library/texmf/tex and download this repository into it.

#Windows
This depends on you LaTeX installation. Instructions for popular distributions can be found with a simple google search.
(Example: [MikTeX](http://tex.stackexchange.com/questions/69483/create-a-local-texmf-tree-in-miktex)) 

## Use
```tex
\documentclass[preview]{standalone}
\usepackage{alchemy}

\begin{document}
	\gold{}
\end{document}
``` 

Symbols available can be found [here](./examples/example.pdf). Full documentation is on its way! 

###Options
```tex
\gold{scale=3, line width=1.5pt, red}
```
Any TikZ options can be placed in the parentheses.
