# methylene

Methylene is a unified collection of minimalist templates for some common academic documents (cv, website, presentations, etc).


## Notes
This package is currently under development, and none of the themes are particularly "mature".
Changes incompatible with past releases should be expected for some time.

Currently the default typefaces are [Lato](http://www.latofonts.com/) and [Vollkorn](http://vollkorn-typeface.com/).
These typefaces were chosen because they are open source and work well on the web and in print.

## Instructions
The `.tex` files use the package `fontspec` which requires `XeLaTeX` (or similar) to compile.

### beamer
copy files to beamer folder of LaTeX: `/usr/share/texlive/texmf-dist/tex/latex/beamer/`, then run `texhash`

### cv
It should be fairly straightowrad to use this template.
Note that some styling has been hard coded, but I plan to make it a bit more flexible in the future.

### poster
coming soon..

### web
The main contribution are the CSS files.
Changing the HTML should be straighforward. 
The CSS is meant to be compatiable with [pandoc](https://pandoc.org/).
For an example of how pandoc can be used to quickly generate an entire website, you can look through the source code of [my website](https://github.com/tchen01/tchen01.github.io).
