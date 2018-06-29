all: loesung1.pdf loesung3.pdf loesung4.pdf loesung6.pdf

loesung1.pdf: loesung1.latex
	latexmk -pdf -use-make $<

loesung3.pdf: loesung3.latex
	latexmk -pdf -use-make $<

loesung4.pdf: loesung4.latex
	latexmk -pdf -use-make -pvc $<

loesung6.pdf: loesung6.latex
	latexmk -pdf -use-make -pvc $<
