all: paper

paper:
	pdflatex report
	bibtex report
	pdflatex report

clean:
	rm -f report.{aux,bbl,blg,log,pdf}
