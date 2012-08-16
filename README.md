The drexel-tech LaTeX Document Class
===========

A LaTeX class for technical reports that follows the Defense Federal Acquisition
Regulation Supplement (DFARS) Clause 252.227-7013 for marking technical data as
well as Drexel University copyright requirements.

* Author: Christopher T. Cannon
* Copyright (C) 2012 Christopher T. Cannon

Compiling
---------

To build the class file (i.e., drexel-tech.cls), template, and example TeX documents, run:

    pdflatex drexel-tech.ins

This will produce the following files:
* drexel-tech.cls: The drexel-tech document class file.
* template.tex: The LaTeX document to 
* example.tex:
* example-draft.tex:
* example-ref.tex:

To compile the documents to produce a PDF document, run:

    latexmk -pdf example.tex
    latexmk -pdf example-draft.tex

To build the documentation, run:

    pdflatex drexel-tech.idx

Usage
-----

To use the drexel-tech document class, copy drexel-tech.cls and template.tex
files to the new working directory of the document and fill in the required
fields noted in template.tex.
