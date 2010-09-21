all: clean prova expectativas

prova: prova.tex
	latex prova
	latex prova
	dvipdf prova
	evince prova.pdf&

expectativas: expectativas.tex
	latex expectativas
	latex expectativas
	dvipdf expectativas
	evince expectativas.pdf&
	
clean: 
	-rm -f *.pdf *.aux *.dvi *.ps *.lo* *.toc *.bbl *.log *.blg *.gl* *.ilg
	-rm -f *.nav *.out *.snm
