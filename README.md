# latex-template
A simple template for LaTeX. By default, the template uses the package minted (available at https://github.com/gpoore/minted), which requires pdfLaTeX to be compiled with -shell-escape flag. Please be aware of what risks the usage of this flag implies.

The template also uses the package biblatex and biber as its backend. If you want to use biblatex, please first compile pdfLaTeX, then biber and then pdfLaTeX once more.

In order to compile, the script mktex, maintained by @tmlarsson, may be used. It is now available at https://github.com/tmlarsson/mktex.
