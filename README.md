# LaTeX Refsheet Template

This is a LaTeX document template for cramming a lot of info on one or two pages for an exam cheat sheet or other quick reference usage. It is forked from [this template](https://github.com/kenfehling/latex-cheatsheet) and fixed with some opinionated revisions and comments.

## Setup

Use [this gist](https://gist.github.com/rain1024/98dd5e2c6c8c28f9ea9d) to help with ubuntu tooling setup.

## Usage
Write section files in the `content` directory. Input them inside the multicols environment in `main.tex` to add them to the document and arrange their ordering. Use your LaTeX compiler of choice (such as [Overleaf](https://www.overleaf.com)) to build the PDF.

You may also need to set the document class in `main.tex` to either `a4paper` or `letter-paper` depending on your print dimensions.

