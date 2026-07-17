UECM3034 NUMERICAL METHODS - LATEX COURSE NOTES

Files
-----
UECM3034_Complete.tex
    Builds the instructor/complete version with worked solutions.

UECM3034_Student.tex
    Builds the student version. Solutions are hidden and replaced by writing space.

uecm3034_full_common.tex
    Shared preamble, title page, theorem/example styles and chapter includes.

chapters/topic1.tex ... chapters/topic8.tex
    Individual chapter source files.

Building
--------
Run twice so that the table of contents is updated:

    pdflatex UECM3034_Complete.tex
    pdflatex UECM3034_Complete.tex

or

    pdflatex UECM3034_Student.tex
    pdflatex UECM3034_Student.tex

The notes were prepared from the UECM3034 June 2026 lecture materials and
expanded into a theorem-example format similar to the supplied combinatorics notes.
