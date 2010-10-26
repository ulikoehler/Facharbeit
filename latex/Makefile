all: viewpdf
pdf:
	pdflatex visualization
	bibtex visualization
	pdflatex visualization
	pdflatex visualization
viewpdf: pdf
	evince visualization.pdf
clean:
	rm *.aux *.bbl *.blg *.log *.backup *.toc *.bib.bak
spellcheck:
	aspell --mode=tex -c visualization.tex
