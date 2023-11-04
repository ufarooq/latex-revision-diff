pdf: diff.tex
	pdflatex diff.tex

latextarget: diff.tex
	latex diff.tex
	bibtex diff
	latex diff.tex
	bibtex diff
	latex diff.tex

all: diff.tex
	pdflatex diff.tex
	bibtex diff
	pdflatex diff.tex
	pdflatex diff.tex

clean:
	rm diff.pdf diff.log diff.aux diff.bbl diff.blg

