latexfile = orthogonal-design

all: prepare pdf

prepare:
	mkdir -p output

pdf: $(latexfile).tex
	xelatex --aux-directory=tmp --output-directory=output $(latexfile).tex

clean:
	rm -rf output

.PHONY: all prepare clean
