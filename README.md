A copy of the template created by @kwlg with some more macros added for mathematics. Also the repository which `mktex` points to.

# latex-template
A simple report and presentation template for LaTeX to be compiled with luaLaTeX.

The template makes use of `tikzexternalize` and the package `minted` (available at https://github.com/gpoore/minted). These are, however, not enabled by default but can be enabled by removing the comments in the beginning of the lines where the externalization is called and the package is loaded. The choice not to load these by default was made because they require the document to be compiled with the `shell-escape` flag. Please be aware of that risks the usage of this flag could imply.

The template also uses the package biblatex and biber as its backend. If you want to use biblatex, please first compile luaLaTeX, then biber and then luaLaTeX once more.

In order to compile, the script `mktex`, maintained by @tmlarsson, may be used. It is now available at https://github.com/tmlarsson/mktex.
