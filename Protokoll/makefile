pdf:
	pandoc protokoll.md -o ./src/protokoll.tex -t latex
	xelatex ./src/main.tex -o protokoll.pdf

pdfandopen:
	pandoc protokoll.md -o ./src/protokoll.tex -t latex
	xelatex ./src/main.tex -o protokoll.pdf
	mupdf main.pdf

clean:
	rm main.aux main.log main.out main.toc


