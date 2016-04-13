all:
	pdflatex miparcours.tex
	bibtex miparcours.aux
	pdflatex miparcours.tex

clean:
	rm miparcours.pdf
	rm miparcours.log
	if [ -e miparcours.blg ]; then rm miparcours.blg; fi
