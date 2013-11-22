multirowbt
==========

This package defines a multirow command for use with booktabs package.

* ``\multirowbt``:
* ``\multirowbt*``:

## Install

* Clone this repository to your homedir
   e.g. ``git clone https://github.com/maphy-psd/multiworbt.git``
* LaTeX run on multirow.ins, e.g.

        pdflatex multirow.ins

## Compile the documention
* LaTeX run on multirow.dtx

        pdflatex multirow.dtx

* Changesection needs a makeindex run

        makeindex -s gglo.ist -o multirow.gls hmultirow.glo

* also the Index

        makeindex -s gind.ist -o multirow.ind multirow.idx

* a another LaTeX run makes the complete documention

        pdflatex multirow.dtx

**Enjoy!**
