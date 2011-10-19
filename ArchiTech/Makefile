all: ArchiTechnique.pdf

clean: cleantmp
	rm ArchiTechnique.pdf 2> /dev/null
	rm *.toc 2> /dev/null

cleantmp:
	rm *.log *.out *.aux 2> /dev/null

ArchiTechnique.pdf: ArchiTechnique.tex
	pdflatex ArchiTechnique.tex
