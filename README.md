# Mémo Python
Mémo regroupant diverses info sur le langage Python écrit en LaTeX. Le PDF résultant se trouve [ici](http://python.pycolore.fr). La version web se trouve [là](http://www.pycolore.fr/python/).

## Roadmap

- [ ] Builtins
- [ ] Bibliothèque standard
  - [ ] `json`
  - [ ] `collections.abc`
  - [ ] `itertools` 
  - [ ] `functools`
  - [ ] `os`
  - [ ] `sys`
  - [ ] `glob`
  - [ ] `subprocess`
  - [ ] `threading`
- [ ] Modules tiers
  - [ ] `pandas`
  - [ ] `click`
- [ ] Django
- [ ] Flask
- [ ] PySide
- [ ] PyGTK

## Compilation

### Fedora

Paquets nécessaires :

```
# dnf install \
    texlive-xetex texlive-latex \
    texlive-sectsty \
    texlive-titlesec \
    texlive-babel-french \
    texlive-minted \
    linux-libertine-fonts \
    linux-libertine-biolinum-fonts
```

Pour compiler :

```
$ xelatex -shell-escape python.tex
```
