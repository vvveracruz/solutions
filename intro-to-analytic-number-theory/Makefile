OUTPDFNAME=intro-to-analytic-number-theory.pdf
BUILDDIR=build

default:
	mkdir -p ${BUILDDIR}
	pdflatex -output-directory=${BUILDDIR} main
	bibtex ${BUILDDIR}/main
	pdflatex -output-directory=${BUILDDIR} main
	pdflatex -output-directory=${BUILDDIR} main
	mv ${BUILDDIR}/main.pdf ./${OUTPDFNAME}

show:
	make
	code ./${OUTPDFNAME}

clean:
	rm -r ${BUILDDIR}/
	rm ./${OUTPDFNAME}