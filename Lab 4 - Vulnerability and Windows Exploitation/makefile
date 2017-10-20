all: writeup

writeup:
	latex CS373LAB1-JonathanHarijanto.tex
	bibtex CS373LAB1-JonathanHarijanto
	latex CS373LAB1-JonathanHarijanto.tex
	latex CS373LAB1-JonathanHarijanto.tex
	dvips -R -Poutline -t letter CS373LAB1-JonathanHarijanto.dvi -o CS373LAB1-JonathanHarijanto.ps
	ps2pdf CS373LAB1-JonathanHarijanto.ps

clean:
	rm -f *.pdf *.ps *.dvi *.out *.log *.aux *.bbl *.blg *.pyg

.PHONY: all show clean ps pdf showps