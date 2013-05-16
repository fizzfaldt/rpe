.PHONY: cbfs.pdf
cbfs.pdf: cbfs.tex
	true && \
	pdflatex $< && bibtex cbfs && \
	pdflatex $< && bibtex cbfs && \
	pdflatex $<

.PHONY: clean
clean:
	rm -rf cbfs.dvi cbfs.bbl cbfs.aux cbfs.log cbfs.pdf cbfs.blg
