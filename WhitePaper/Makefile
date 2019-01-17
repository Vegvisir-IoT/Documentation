FLAGS=-interaction=nonstopmode

notarealfile.pdf:
	pdflatex ${flags} veg_white.tex
	pdflatex ${flags} veg_white.tex
	bibtex veg_white.aux
	pdflatex ${flags} veg_white.tex
	pdflatex ${flags} veg_white.tex


clean:
	rm -f *.dvi
	rm -f *.aux
	rm -f *.log
	rm -f *.toc
	rm -f *.idx
	rm -f Contents/*.aux
	rm veg_white.pdf

