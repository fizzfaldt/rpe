bfs.pdf: bfs.tex sections/*.tex
	true && \
	pdflatex $< && bibtex bfs && \
	pdflatex $< && bibtex bfs && \
	pdflatex $<

.PHONY: clean
clean:
	rm -rf bfs.dvi bfs.bbl bfs.aux bfs.log bfs.pdf bfs.blg
