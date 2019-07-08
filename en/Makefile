PAPER = sample-sigplan
TEX = $(wildcard *.tex)

.PHONY: all clean

$(PAPER).pdf: $(TEX)
	pdflatex $(PAPER)

clean:
	rm -f *.aux *.cut *.log *.out $(PAPER).pdf

