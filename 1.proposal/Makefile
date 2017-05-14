all:
	make proposal

proposal: related/*.tex
	latexmk -pdf proposal.tex
	make clean

clean:
	rm -f *.fdb_latexmk *.fls *.dvi *.aux *.log *.toc *.glo *.idx *.ilg *.out *.bbl *.thm *.blg *.lot *.lof
	rm -rf related/*.aux