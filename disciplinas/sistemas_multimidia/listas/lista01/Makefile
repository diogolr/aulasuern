all: clean lista

lista: lista.tex
	latex lista
	latex lista
	dvipdf lista
	evince lista.pdf&
	
clean: 
	-rm -f *.pdf *.aux *.dvi *.ps *.lo* *.toc *.bbl *.log *.blg *.gl* *.ilg
	-rm -f *.nav *.out *.snm
