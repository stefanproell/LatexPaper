LatexPaper
==========

This is a Latex Paper Template

Compiling the paper
===================

This template provides [arara](https://github.com/cereda/arara) markups for compilation. The main document file contains the following self explaining markups:

    % arara: pdflatex: { shell : yes }
    % arara: bibtex
    % arara: pdflatex: { shell : yes }
    % arara: pdflatex: { shell : yes }



    stefan@desktop:~/workspaceGIT/LatexPaper$ arara NewPaper
      __ _ _ __ __ _ _ __ __ _ 
     / _` | '__/ _` | '__/ _` |
    | (_| | | | (_| | | | (_| |
     \__,_|_|  \__,_|_|  \__,_|

    Running PDFLaTeX... SUCCESS
    Running BibTeX... SUCCESS
    Running PDFLaTeX... SUCCESS
    Running PDFLaTeX... SUCCESS
