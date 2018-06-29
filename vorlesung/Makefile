all: mitschrift.pdf

live: mitschrift.latex
	latexmk -pdf -use-make -pvc $<

mitschrift.pdf: mitschrift.latex
	latexmk -pdf -use-make $<
