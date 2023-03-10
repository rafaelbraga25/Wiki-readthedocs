# Wiki-readthedocs

## Instalação

### Sphinx

```
apt-get install python3-sphinx

or

pip install sphix
```

### Readthedocs theme

```
pip install sphinx_rtd_theme
```

### Criar projeto sphinx

```
sphinx-quickstart
``` 

### Aplicar tema Readthedocs

In your Sphinx project’s `conf.py` file, add `sphinx_rtd_theme` to the list of enabled extensions and as the active theme:

```python
extensions = [
    ...
    'sphinx_rtd_theme',
]

html_theme = "sphinx_rtd_theme"
```

### Build do projeto

```
sphinx-build -b html sourcedir builddir
```
