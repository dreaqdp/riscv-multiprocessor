
all: report

report: 
	latexmk -g -pdf 00_report.tex

clean:
	latexmk -c

clean_all: clean
	latexmk -C

run: 
	xdg-open *.pdf &> /dev/null &
