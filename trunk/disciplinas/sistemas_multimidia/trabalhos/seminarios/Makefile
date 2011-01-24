all: clean seminarios

seminarios: seminarios.tex
	latex seminarios
	latex seminarios
	dvipdf seminarios
	evince seminarios.pdf&
	
clean: 
	-rm -f *.pdf *.aux *.dvi *.ps *.lo* *.toc *.bbl *.log *.blg *.gl* *.ilg
	-rm -f *.nav *.out *.snm
