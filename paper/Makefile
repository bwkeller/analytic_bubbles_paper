paper.pdf: paper.aux paper.bbl
	pdflatex paper.tex

paper.aux: paper.tex
	pdflatex paper.tex

paper.bbl: paper.aux
	bibtex paper.aux

