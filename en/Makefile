PAPER = sample-sigplan
TEX = $(wildcard *.tex)

.PHONY: all clean

all: $(TEX)
	pdflatex $(PAPER)

clean:
	rm -f *.aux *.cut *.log *.out $(PAPER).pdf

