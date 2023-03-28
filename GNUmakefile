.SUFFIXES: .qmd .html
.PHONY: html clean

.qmd.html:
	quarto render $<

all: html

html: integration_modules.html

clean:
	rm -rf integration_modules.html integration_module_files


