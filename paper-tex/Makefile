buildlatex=pdflatex -shell-escape

all:
	$(buildlatex) 01-Requirements-Engineering.tex
	bibtex 01-Requirements-Engineering
	$(buildlatex) 01-Requirements-Engineering.tex
	$(buildlatex) 01-Requirements-Engineering.tex
