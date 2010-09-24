all: clean implementacao

implementacao: implementacao.tex
	latex implementacao
	latex implementacao
	dvipdf implementacao
	evince implementacao.pdf&
	
clean: 
	-rm -f *.pdf *.aux *.dvi *.ps *.lo* *.toc *.bbl *.log *.blg *.gl* *.ilg
	-rm -f *.nav *.out *.snm
