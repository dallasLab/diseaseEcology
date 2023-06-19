

all:
	- Rscript -e "files <- grep('Rmd', list.files(), value=TRUE); library(rmarkdown); sapply(files, render)"


pdf: 
	- Rscript -e "files <- grep('Rmd', list.files(), value=TRUE); library(rmarkdown); sapply(files, render, 'pdf_document', output_dir='../../lecturePDF')"
