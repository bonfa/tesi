FILENAME=thesis
SOURCES=./$(FILENAME).tex
BIN=./$(FILENAME).pdf
TEMP_FILES= thesis.idx thesis.log thesis.aux  thesis.lof  thesis.out thesis.toc
CC=pdflatex
CC_BIB=bibtex

all: tesi
	
tesi: 
	$(CC) $(SOURCES) && rm $(TEMP_FILES) && evince $(BIN)

view:
	evince $(BIN)

clean:
	rm $(TEMP_FILES)

debug:
	$(CC) $(SOURCES)

