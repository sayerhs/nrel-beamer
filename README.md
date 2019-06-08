
# Beamer template for NREL presentations 

This repository contains a beamer template for generating
[NREL](https://www.nrel.gov) presentations with
[LaTeX](http://latex-project.org).

## Installation and usage

The main entry point for the beamer document is `main.tex`. Make appropriate
changes and run `make` to generate a PDF of the formatted presentation. By
default, `make` will use `pdflatex` to compile the latex sources, please edit
`Makefile` to change this or add additional for `pdflatex`. The beamer design
code is contained in `beamerthemeecp.sty` following Beamer guidelines for
generating new themes.

### Misc. Tips

- Use `\maketitle` to generate the title page from `\title`, `\author`,
   `\institution`, and `\date` entries in `main.tex`.

- Use `\section{Transition Slide Title}` to add a transition slide

- Use `\nrelacknowledge{}` to enter standard acknowledgements slide in the
  presentation. Additional acknowledgement paragraphs can be passed as an
  argument to the `\nrelacknowledge` command.
  
## Image copyright

All images in `nrel_theme` directory are copyright [NREL](https://www.nrel.gov).
Please consult NREL regarding their usage.
