
# Description

This project provides the colour definitions introduced by the 
[ColorBrewer project](http://colorbrewer2.org/) 
for use in 
[TikZ](http://sourceforge.net/projects/pgf/) 
and 
[pgfplots](http://pgfplots.sourceforge.net/).

# Installation

Simply put the files in a directory where LaTeX can find your files. On linux,
for example, put these files in `~/texmf/tex/latex/colorbrewer/` (you might have
to create the directory). Then run `texhash` to update the definitions.

# Usage

There are two example files `display_colorcycle.tex` and `display_colors.tex`
which illustrate the usage. The second example outputs a list of all colours.
