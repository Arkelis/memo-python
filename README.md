# Mémo Python
Mémo regroupant diverses info sur le langage Python écrit en LaTeX. Le PDF résultant se trouve [ici](http://python.pycolore.fr). La version web se trouve [là](http://www.pycolore.fr/python/). Le dépôt contenant la configuration permettant de passer de la version LaTex à la version Web se trouve [dans ce dépôt](https://github.com/Arkelis/memo-python-sphinx-conf).

## Feuille de route

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

## Compilation en PDF

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

## Compilation Web

Voir [dans ce dépôt](https://github.com/Arkelis/memo-python-sphinx-conf).
