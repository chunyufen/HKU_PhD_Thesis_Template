# HKU PhD Thesis Template

## Introduction

This is not an official template published by The Hong Kong University, Pokfulam.

The first version was uploaded in May 2018. This is an updated version in November 2024.

This is a test XeLatex template for PhD students of The University of Hong Kong.
The compilation process is:
XeLatex -> Bibtex -> Xelatex -> Xelatex.

It is the duty of a student to check the Guide for MPhil and PhD Students for Preparing and Submitting Your Thesis. This Guide is now available only to current students.

When I prepared this test template, the Guide is freely available on the internet.

## Structure of the thesis

This test template, as an example, demonstrates 8 chapters.

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

  1. Chapter 6 (Method 2)

  1. Chapter 7 (Data Analysis and Findings)
  
  1. Chapter 8 (Summary, Conclusions and Recommendations)

  1. Appendix A (if applicable)

  1. Appendix B (if applicable)
  
  1. Appendix C (if applicable)

  1. Bibliography

## Relationships of files

The main document is "main.tex". The bibliography data file (.bib) stays alongside with "main.tex".

The folder "appendix" contains Appendix A, Appendix B and Appendix C.

The folder "chapters" contains the eight chapters (including the conclusion).

The folder "frontMatters" contains the files with names: "acronym.tex", "abstract.tex", "acknowledgment.tex", "dedication.tex", "contents.tex", "declaration.tex", "publication.tex" and "titlePage.tex".

The folder "imageFiles" contains all the image files for the thesis.

The title of the thesis and the Chinese and English names of the student are contained in the files "titlePage.tex" and "abstract.tex".

Lines 58 to 60 of the file "main.tex" changes the Chinese font.

Line 127 of the file "main.tex" changes line spacing.

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

If the Chinese fonts (UTF-8) do not show properly, you may have to change line 58 of the file "main.tex" to, for example, a font used by your computer:

  - \setCJKmainfont{標楷體} or
  - \setCJKmainfont{SimSun}

The current setting is:

  - \setCJKmainfont[Scale=0.9]{Songti TC}

## List of acronyms (newly added)

List of acronyms was added.

## Amendments to Acknowledgment

Some universities require acknowledgment of use of AI Generative materials, for example:

- [Advice to help you transparently acknowledge Artificial Intelligence in your academic work.](https://www.ncl.ac.uk/academic-skills-kit/good-academic-practice/artificial-intelligence/acknowledging/) (Newcastle University)
- [Acknowledging AI tools and technologies.](https://students.unimelb.edu.au/academic-skills/resources/academic-integrity/acknowledging-AI-tools-and-technologies) (The University of Melbourne)
- [Referencing and acknowledging the use of artificial intelligence tools.](https://www.student.unsw.edu.au/ai-referencing) (The University of New South Wales)
- [Acknowledging the use of generative artificial intelligence.](https://www.monash.edu/student-academic-success/build-digital-capabilities/create-online/acknowledging-the-use-of-generative-artificial-intelligence) (Monash University)
- [Acknowledge Use of AI-Generated Content.](https://libguides.eduhk.hk/scite/acknowledge) (The Education University of Hong Kong)
- [Acknowledging use of AI tools in research and assignments.](https://libguides.adelaide.edu.au/c.php?g=959585&p=6965121) (The University of Adelaide)
- [Acknowledging AI sources, page 9.](https://www.cambridgemaths.org/Images/engaging_with_artificial_intelligence_in_research_and_writing.pdf) (Cambridge University)
- [Best Practices for Ethical and Responsible Use of Generative Artificial Intelligence (AI) Tools in Course Assessments, page 2.](https://www.ln.edu.hk/tlc/f/page/51687/AI%20Practice_updated%2024%20Jul%202023_final.pdf) (Lingnan University)
- [Acknowledging the use of GAI in your work](https://www.dundee.ac.uk/guides/use-generative-artificial-intelligence-students) (University of Dundee)
- [Declaration of AI generated material](https://www.jcu.edu.au/students/learning-centre/during-the-study-period/academic-integrity/generative-artificial-intelligence) (James Cook University)
- [How do I acknowledge use of generative AI?](https://www.kcl.ac.uk/about/strategy/learning-and-teaching/ai-guidance/student-guidance) (King's College London)
- [Acknowledging and referencing and generative AI tools.](https://www.imperial.ac.uk/admin-services/library/learning-support/generative-ai-guidance/) (Imperial College London)

Therefore, the "Acknowledgment" was recently amended. A student has the duty to check with university and supervising professor regarding the use of AI Generative materials.

## Appendix C (newly added)

Appendix C is a schedule particularising each of the occasions for the use of Generative AI for writing this thesis.

## Other amendments

Other amendments are typographical mistakes, together with function names.


