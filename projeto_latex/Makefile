FILE = Projeto

all :
	pdflatex $(FILE)
	#makeindex $(FILE).nlo -s nomencl.ist -o $(FILE).nls
	bibtex $(FILE)
	pdflatex $(FILE)
	pdflatex $(FILE)
	mv $(FILE).pdf projeto_bepe.pdf
	rm *.aux *.bbl *.log *.blg *.out
clean:
	rm *.aux *.bbl *.log *.blg *.out

