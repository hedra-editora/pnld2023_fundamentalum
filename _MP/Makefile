all:
	latexmk -xelatex $(file).tex
	evince $(file).pdf &
	open $(file).pdf 
	
clean:
	rm *.xwm *.xdv *.out *aux *.log *tui *toc *.4ct *.4tc *.html *.css *.dvi *.epub *.lg *.ncx *.xref *.tmp *.idv *.opf *.fdb_latexmk *.fls *.ind
