
all: presentation

doc: 
	latexmk -g -pdf 00_doc.tex


presentation: 
	latexmk -g -pdf presentation.tex

clean:
	latexmk -c

clean_all: clean
	latexmk -C

run: 
	xdg-open *.pdf &> /dev/null &
