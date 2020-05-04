#
#	MAKEFILE
#	
# 	Autor: 	Dominik Horky
# 	Datum: 	12.4.2020
#
# 	Urceno pro prekladani projektu do predmetu ITY (s jedinym zdrojovym .tex souborem!)
#	(mirne upraveno pro 5. projekt)

INPUT := $(shell ls *.tex | cut -d "." -f 1)

pdf: $(INPUT).pdf
	
$(INPUT).pdf: $(INPUT).tex
	pdflatex $(INPUT).tex
clean:
	rm -rf *.aux *.log *.nav *.out *.pdf *.snm *.toc
