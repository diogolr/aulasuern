all: clean aula

aula: aula.tex
	latex aula
	latex aula
	dvipdf aula
	evince aula.pdf&
	
clean: 
	-rm -f *.pdf *.aux *.dvi *.ps *.lo* *.toc *.bbl *.log *.blg *.gl* *.ilg
	-rm -f *.nav *.out *.snm
