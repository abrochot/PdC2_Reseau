TARGET=ArchiTechnique.pdf
INCLUDES=Concepts.tex Logiciel.tex Materiel.tex
ASSETS=Existant.png Transition.png Cible.png
TEXFILE=ArchiTechnique.tex

all: $(TARGET)

clean: cleantmp
	rm -f $(TARGET) *.toc *.ind *.dvi

cleantmp:
	rm -f *.log *.out *.aux *.ilg

$(TARGET): $(TEXFILE) $(INCLUDES) $(ASSETS)
	#Once for toc, hyper-refs, etc, and once for good
	pdflatex $(TEXFILE)
	pdflatex $(TEXFILE)
