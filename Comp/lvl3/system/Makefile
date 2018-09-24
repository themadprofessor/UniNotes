MDC=pandoc
MDCFLAGS=-s
SRCFILES=paradigms.md compilation.md

%.html : %.md
	$(MDC) $< -f commonmark -t html $(MDCFLAGS) -o $@

html: $(patsubst %.md, %.html, $(SRCFILES))

clean:
	rm *.html
