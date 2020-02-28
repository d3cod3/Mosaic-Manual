# Mosaic Manual

The scope of the manual is the Mosaic application.

## Contributions

Send a pull request to this repository with your edits.
Major changes like new pages and complete overhauls are welcome, as well as minor fixes like grammar, spelling, and reorganization.
Your PR will be accepted if it is a net positive benefit to readers.

## Building

Install [Sphinx](http://www.sphinx-doc.org/en/stable/) 1.8.1. Newer versions do not generate formulas and image tags properly.

```bash
pip install sphinx==1.8.1
pip install sphinx-markdown-tables
pip install sphinx_rtd_theme
```

Install [recommonmark](https://github.com/rtfd/recommonmark) 0.4.0.

```bash
pip install recommonmark==0.4.0
```

Build with

```bash
make html
```  

The output should be generated in `_build/html`.

## License

All documentation text in this repository is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
