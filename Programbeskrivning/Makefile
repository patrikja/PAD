default: TKDAT_programbeskrivning_Datateknik_Chalmers.pdf

%.pdf: %.tex
	latexmk -pdf $<

clean:
	-rm *.fdb_latexmk *.aux *.log *.out
