1all:
	pdflatex final.tex
	bibtex final.aux
	pdflatex final.tex

clean:
	rm final.pdf
	rm final.log
	if [ -e final.blg ]; then rm final.blg; fi
