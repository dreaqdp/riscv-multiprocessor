
all: presentation

presentation: 
	latexmk -g  -pdf 00_presentation.tex

clean:
	latexmk -c

clean_all: clean
	latexmk -C

run: 
	xdg-open *.pdf &> /dev/null &
