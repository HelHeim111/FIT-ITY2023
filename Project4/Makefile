FILE_NAME = proj4

all:
	latex $(FILE_NAME).tex
	bibtex $(FILE_NAME).aux
	latex $(FILE_NAME).tex
	latex $(FILE_NAME).tex
	dvips $(FILE_NAME).dvi
	ps2pdf -sPAPERSIZE=a4 $(FILE_NAME).ps

clean:
	rm -f $(FILE_NAME).{out,log,aux,pdf,ps,dvi}