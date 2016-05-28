all: Questions.pdf

clean:
	rm -f *.aux *.toc *.log *.out

%.pdf: %.tex
	pdflatex -output-directory .. $<
	pdflatex -output-directory .. $<
