all: clean apostila

apostila: apostila.tex
	latex apostila
	#makeindex -s makeglo.ist -o apostila.gls apostila.glo
	#bibtex apostila 
	latex apostila
	latex apostila
	dvipdf apostila
	evince apostila.pdf&

clean: 
	-rm -f *.pdf *.aux *.dvi *.ps *.lo* *.toc *.bbl *.log *.blg *.gl* *.ilg *.out
	-rm -f *.nav *.snm
