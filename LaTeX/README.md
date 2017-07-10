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

### Possible Document Classes
Class Name | Description
--- | ---
article | For articles, scientific journals, invitations.
proc | Proceedings class based on article
report | longer documents that partition into sections/subsections (theses, small books).
book | Full-sized books
slides | Specializes in larger fonts like a powerpoint slide deck.
letter | For letters


