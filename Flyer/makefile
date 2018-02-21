pdf:
	pandoc filmflyer.md -o ./src/filmflyer.tex -t latex
	xelatex ./src/main.tex -o filmflyer.pdf

pdfandopen:
	pandoc filmflyer.md -o ./src/filmflyer.tex -t latex
	xelatex ./src/main.tex -o filmflyer.pdf
	mupdf main.pdf

clean:
	rm main.aux main.log main.out main.toc


