SPHINXOPTS    =
SPHINXBUILD   = sphinx-build
SOURCEDIR     = .
BUILDDIR      = _build


all: html

run: html
	http-server _build/html

upload: html
	rsync _build/html/ mosaic.d3cod3.org/manual/ -ruvz --delete

%:
	@$(SPHINXBUILD) -M $@ "$(SOURCEDIR)" "$(BUILDDIR)" $(SPHINXOPTS)
