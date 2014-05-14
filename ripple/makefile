all: bibtex pdflatex

bibtex: ripple.tex ripple.bib
	pdflatex ripple
	bibtex ripple
	
pdflatex: bibtex
	pdflatex ripple
	pdflatex ripple
