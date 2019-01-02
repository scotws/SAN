# Simpler Assembler Notation (SAN) for the 6502, 65c02, and 65816
Scot W. Stevenson <scot.stevenson@gmail.com>   
First version: 09. Oct 2015 
This version: 02. Jan 2018

This folder contains the specification for an alternative, quite
possibly improved notation for the 6502, 65c02, and especially 65816 family
of processors. It is used by (cough) me in various programs. 

The original document is in AsciiDoc as `san_handbook.adoc` and provided in
additional format, currently HTML, PDF and GitHub markdown (`.md`). The HTML
document is the primary version. Conversion for HTML and PDF is handled
automatically as:

- HTML: `asciidoctor -a toc=left san_handbook.adoc`
- PDF:  `asciidoctor-pdf -v san_handbook.adoc`

Converting to GitHub's markdown is tricker than you would think. There is an
experimental script included in this folder, `asciidoc_to_markdown.sh`, that
however eats the title line for some reason. This must be added by hand at
the moment. See https://github.com/asciidoctor/asciidoctor/issues/1907
