# LaTeX

The Language for typesetting documents.

Most of these notes are concerned specifically with generating pdf files in `pdflatex`.

# CONTENTS
* [Boilerplate](#Boilerplate)
* [Setting Up Documents](#Setup)
* [Document Metadata](#Metadata)
* [Whitespace](#Whitespace)
* [Rich Text](#Text)


# Boilerplate

For those who just want to get started, the following layout will create a basic pdf document for typesetting.

```
\documentclass{article}

\begin{document}

This is a basic document. Replace text here to make it typeset into a pdf.

\end{document}
```


# Setup

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
twocolumn | typesets two columns instead of one. | N/A
twoside,oneside | Determines whether or not document is intended to be printed multisided. | twoside for book, oneside for everything else
landscape | Changes paper to sideways (landscaped) alignment. | N/A
openany, openright, openleft | Makes chapter sections begin on next available page, next right hand page, next left hand page respectively. | openright for book, open any otherwise.
draft | Enables draft markers. Marks edits in a box in document corner. | N/A

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


# Metadata

Once you've created a document, you might want to attach some identifying information to it.
Before the body of your document begins, you may want to ad some identifying information.
You can specify data with the `\title`, `\author`, and `\date` tags.

After specifying title information, you can print out this header with `\maketitle`.

```
\documentclass[12pt, letterpaper, oneside]{article}

\title{Hello Document}
\author{Douglas Smith \thanks{Github backers}}
\date{July 2017}

\begin{document}

\maketitle

This is where the document body begins.
\end{document}
```


# Whitespace

Latex attempts to arrange text as efficiently as possible, so line breaks need to be explicitly specified.


# Rich Text

Text can be assigned different properties to change its size and emphasis.

### Text Modifiers
Tag | Effect
--- | ---
\textbf{} | **Bold** 
\textit{} | _italics_
\underline{} | underline
\emph{} | Special emphasis(exact text varies)

### Text Sizes
Tag | Size
--- | ---
{\tiny} | Smallest text can be made.
{\footnotesize} | Appropriate footnote sizes.
{\small} | Smaller than regular text.
{\normalsize} | Asserts the size stay average.
{\large} | Larger than standard text size.
{\Large} | Slightly larger than lowercase large.
{\LARGE} | Larger than highest Large.
{\huge} | Bigger than any of the larges.
{\Huge} | More Huge-er.

```
\textbf{This text is Bold.} \newline\textit{This text is italicized.} \newline\underline{This text should be underlined.} \newline\emph{This text has emphasis.} \newline


{\Huge This text will be Huge.} \\
\Huge{This is the same huge text.}\\
{\huge Slightly less impressive is text that is merely huge.}\\
{\LARGE This new text is LARGE. }\\
{\Large Large text is pretty big, but not as big.}\\
{\large Lowercase large text is the smallest of the large text.}\\
{\normalsize This text should be exactly normal}\\ Here is unformatted text for comparison
.\\
{\small This text is smaller than normal.}\\
{\footnotesize This smaller test is perfect for footnotes.}\\
{\tiny This text is tiny.} \\
 
```








