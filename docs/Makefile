# https://github.com/jgm/pandoc/wiki/Pandoc-Tricks#using-markdown-templates
F=$(shell ls *.md)
G=$(F:.md=.html)

all: $G

%.html : %.md
	cat etc/header $< | \
	pandoc --toc -V toc-title:"Table of Contents" --template=./etc/template.markdown -o $@
