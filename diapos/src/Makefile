
TEX = clase
 
$(TEX).pdf: clase.tex header.tex ./slides/*.tex
	pdflatex -shell-escape $(TEX).tex

.PHONY: clean
clean:
	rm -f *.pdf *.aux *.nav *.snm *.log *.out *.toc *.synctex.gz
