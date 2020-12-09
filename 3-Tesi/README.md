# Tesi

Questa cartella contiene la mia tesi della laurea triennale in Informatica.

Nel nostro caso la tesi è una relazione del progetto di stage della durata di ~300h effettuato alla fine del percorso di studi.

Il template utilizzato proviene dal FIUP: [FIUP/Thesis-template](https://github.com/FIUP/Thesis-template).

## Comando di compilazione

La tesi utilizza il package `minted`, che ha bisogno di `--shell-escape`

Quindi per esempio il comando di default:
```
pdflatex -synctex=1 -interaction=nonstopmode %.tex
```
diventerà
```
pdflatex -synctex=1 -interaction=nonstopmode --shell-escape %.tex
```
