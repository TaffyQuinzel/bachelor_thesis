all:
	xelatex mandate.tex -output-directory=build
	bibtex mandate
	xelatex mandate.tex -output-directory=build
	xelatex mandate.tex -output-directory=build
	mv *.aux build/
	mv *.log build/
