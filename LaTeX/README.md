# LaTeX

The Language for typesetting documents.

Most of these notes are concerned specifically with generating pdf files in `pdflatex`.

# CONTENTS
* [Boilerplate](#Boilerplate)
* [Setting Up Documents](#Setting Up Documents)
* []()


# Boilerplate

For those who just want to get started, the following layout will create a basic pdf document for typesetting.

```
\documentclass{article}

\begin{document}

This is a basic document. Replace text here to make it typeset into a pdf.

\end{document}
```


# Setting Up Documents

LaTeX documents start with a `\documentclass[options]{class}` to denote the particulars of this document's typesetting.

The options and class allow certain global settings to be assigned when typesetting the document.
Selecting them appropriately can make setting up the rest of the document fairly simple.

### Document Options

A list of options are specified for the documentclass.

Option Title | Effect | Default
--- | --- | ---
(n)pt | Sets size of main font for document. Should be assigned to the most used font sized. | 10pt
letterpaper,a4paper,a5paper,b5paper,executivepaper, legalpaper | Defines paper size. | letterpaper
fleqn | Typesets formulas to left instead of cntered. | N/A
leqno | Places formula numbers on left instead of right. | N/A
titlepage,notitlepage | Specifies whether or not there is a title page specified. | titlepage in book/report, notitlepage otherwise
twocolumn | typesets two columns instead of one. | None
twoside,oneside | Determines whether or not document is intended to be printed multisided. | twoside for book, oneside for everything else
landscape | Changes paper to sideways (landscaped) alignment. | None
openany, openright, openleft | Makes chapter sections begin on next available page, next right hand page, next left hand page respectively. | openright for book, open any otherwise.
draft | Enables draft markers. Marks edits in a box in document corner. | None

### Possible Document Classes

Only one document class can be selected.

Class Name | Description
--- | ---
article | For articles, scientific journals, invitations.
proc | Proceedings class based on article
report | longer documents that partition into sections/subsections (theses, small books).
book | Full-sized books
slides | Specializes in larger fonts like a powerpoint slide deck.
letter | For letters


