all: viewpdf
pdf:
	pdflatex visualization
	bibtex visualization
	pdflatex visualization
	pdflatex visualization
viewpdf: pdf
	okular visualization.pdf
clean:
	rm *.aux *.bbl *.blg *.log *.backup *.toc *.bib.bak *.brf *.lof -f
spellcheck:
	aspell --mode=tex -c visualization.tex
