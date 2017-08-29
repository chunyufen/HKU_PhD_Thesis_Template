# HKU PhD Thesis Template

## Introduction

This is a XeLatex template for PhD students of The University of Hong Kong.
The compilation process is:
XeLatex -> Bibtex -> Xelatex -> Xelatex.

The Guide for MPhil and PhD Students for Preparing and Submitting Your Thesis
is available [here](http://www.gradsch.hku.hk/gradsch/f/page/510/preparing-thesis2.pdf).

## Structure of the thesis

The template, as an example, demonstrates 5 chapters.

The structure of the template is:

  1. Abstract

  1. Title page of thesis

  1. Dedication

  1. Declarations

  1. Acknowledgments

  1. (optional) Publications

  1. Table of Contents

  1. List of Figures

  1. List of Tables

  1. Chapter 1 (Introduction and the Problem)

  1. Chapter 2 (Literature Review)

  1. Chapter 3 (Background to study population)

  1. Chapter 4 (Method 1)

  1. Chapter 5 (Data Analysis and Findings)

  1. Chapter 6 (Method 1)

  1. Chapter 7 (Data Analysis and Findings)
  
  1. Chapter 8 (Summary, Conclusions and Recommendations)

  1. Appendix A (if applicable)
 
  1. Appendix B (if applicable)

  1. Biblography

## Relationships of files

The main document is "main.tex".

The folder "appendix" contains Appendix A and Appendix B.

The bibilography data file (.bib) stays with "main.tex".

The folder "chapters" contains the six chapters (including the conclusion).

The folder "frontMatters" contains the "abstract.tex", "acknowledgment.tex", "dedication.tex", "contents.tex", "declaration.tex", "publication.tex" and "titlePage.tex".

The folder "imageFiles" contains all the image files for the thesis.

The title of the thesis and the Chinese and English names of the student are contained in the files "titlePage.tex" and "abstract.tex".

Line 58 of the file "main.tex" changes the Chinese font.

Line 124 of the file "main.tex" changes line spacing.

The file "main.tex" contains further explanations and comments.

*All files are saved in Unicode (UTF-8).*

## How many chapters for a thesis

It is said that a conventional PhD thesis has typically the following chapters:

  - Chapter 1: Introduction and outline of the problem

  - Chapter 2: Literature review of subject area

  - Chapter 3: Background to study population or area

  - Chapter 4: Methodological chapter

  - Chapters 5 to 7: Results and discussions chapters (usually 2 or 3)

  - Chapter 8: Conclusion and implications for policy and/or further research 

## If Chinese fonts do not show properly

If the Chinese fonts (UTF-8) do not show properly, you may have to change line 58 of the file "main.tex" to, for example a font used by your computer:

  - \setCJKmainfont{標楷體}

The current setting is:

  - \setCJKmainfont{Yuanti TC Light}

## Other parts that may be added

Lists of Abbreviations and List of Symbols may be added immediately after List of Tables.

Endnotes may be added immediately before Biblography.




