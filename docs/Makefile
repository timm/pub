F=$(shell ls *.md)
G=$(F:.md=.html)

all: $G

%.html : %.md
	cat etc/header $< | \
	pandoc  --css=etc/pandoc.css  -t html -o $@
	
