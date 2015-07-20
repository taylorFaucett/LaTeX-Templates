# LaTeX-Templates

Included are a LaTeX template for course notes and course homework. 

## Course Notes Template

The Course notes template relies on the notes.sty file. This needs to be placed in the same folder/directory as the .tex file which will be using it or in your TeX tree. The style file includes the packages:

* amsmath
* amssymb
* amsthm
* amsfonts
* xcolor
* inputenc
* fontenc
* lmodern
* nameref
* mdframed
* adjustbox
* fancyhdr

as such, you will not need to load these packages separately. Additionally, notes.sty includes a *proof* and *example* environment which will provide you a boxed/colored environment to separate your proofs/examples from your main content. 

![Example Environment](/exxample_environment.png)

## Homework Template

The Homework template is a modified version of the hmcpset class created by the math department of [Harvey Mudd College](https://www.math.hmc.edu/computing/support/tex/classes/hmcpset/). This needs to be placed in the same folder/directory as the .tex file which will be using it or in your TeX tree. The style file includes the packages:

* ifpdf
