all: bibtex pdflatex

bibtex: Tat.tex Tat.bib
	pdflatex Tat
	bibtex Tat
	
pdflatex: bibtex
	pdflatex Tat
	pdflatex Tat
	
clean:
	rm -f Tat.bbl
