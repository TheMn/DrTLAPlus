# Persian Documentation for Paxos with TLA+

This directory contains a paper on the Paxos algorithm, written in Persian. The paper details an implementation of Paxos using TLA+ and appears to be a university project.

## Contents

- `Paxos.tex`: The main LaTeX source file for the paper.
- `neurips.sty`: A LaTeX style file used for formatting.
- `Photos/`: A directory containing images included in the paper.
- `*.ttf`: Font files (XB Yas) required to compile the document.

## Compiling the Document

To generate a PDF from the source files, you will need a LaTeX distribution that supports `xepersian` (e.g., TeX Live). Due to the use of custom fonts, you must compile the document using `xelatex`.

Run the following command in this directory:
```bash
xelatex Paxos.tex
```

This will produce a `Paxos.pdf` file.

## Disclaimer

This document is a community contribution and is not part of the official "Dr. TLA+ Series" lectures. It was forked from another repository and added here for reference.
