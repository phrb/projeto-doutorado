petabricks.pdf: petabricks.tex
	pdflatex petabricks.tex
	makeindex petabricks.tex
	pdflatex petabricks.tex
	bibtex petabricks.aux
	pdflatex petabricks.tex

## Remove unnecessary files
clean:
	-rm -f *.log *.aux *.out *.blg *.bbl *.nav *.snm *.toc *.ind *.ilg *.dvi
	
