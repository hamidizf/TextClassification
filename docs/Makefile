# Makefile
# From https://danielkaes.wordpress.com/2009/03/14/compiling-latex-documents-using-makefiles/

TEX=C:\MiKTeX\miktex\bin\x64\pdflatex
BIBTEX=C:\MiKTeX\miktex\bin\x64\bibtex
BUILDTEX=$(TEX) main.tex
BUILDBIB=$(BIBTEX) main


all:
	${BUILDTEX}
	${BUILDBIB}
	${BUILDTEX}
	${BUILDTEX}



clean-all:
	rm -f *.dvi *.log *.bak *.aux *.bbl *.blg *.idx *.ps *.eps *.pdf *.toc *.out *~

clean:
	rm -f *.log *.bak *.aux *.bbl *.blg *.idx *.toc *.out *~