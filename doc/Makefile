.PHONY: all clean


LATEX = pdflatex
PDFS = informe.pdf

all: $(PDFS)

%.pdf: %.tex
	$(LATEX) $<

clean:
	rm -rf ./*.aux ./*.log ./*.tex~ ./*.toc ./*.pdf ./*.tex.backup ./*.snm ./*.vrb ./*.nav ./*.out ./*.fdb_latexmk ./*.maf ./*.mtc ./*.mtc0 ./*.synctex.gz ./*.fls ./*.blg
