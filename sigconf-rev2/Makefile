pdf: main.tex
	pdflatex main.tex

latextarget: main.tex
	latex main.tex
	bibtex main
	latex main.tex
	bibtex main
	latex main.tex

all: main.tex
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex

clean:
	rm main.pdf main.log main.aux main.bbl main.blg

