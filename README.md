# Ingegneria del Software

Progetto LaTeX che comprende una serie di concetti di Ingegneria del Software, UML e Design Pattern.

Per sapere se l'argomento che cerchi è presente in questa dipensa [guarda il programma](./PROGRAMMA.md)

## Download

Per scaricare il file PDF compilato scegli la versione che preferisci nella sezione [release](https://github.com/angelobdev/dispensa-ingsoft/releases/) oppure [clicca qui](https://github.com/angelobdev/dispensa-ingsoft/releases/download/v2.0/IngSoft-v2.0.pdf)

## Guida di compilazione (VSCode)

### Prerequisiti

1. [TexLive Manager](https://www.tug.org/texlive/tlmgr.html)
2. Librerie di compilazione: [latexmk](https://mgeier.github.io/latexmk.html)
3. Librerie progetto: tocbibind, titlesec, minted
4. [PDFLatex](https://www.tug.org/applications/pdftex/)

**Nota:**  
Su macOS puoi installarli tramite [Homebrew](https://brew.sh/)

```sh
  # TeX Live e PDFLatex
  brew install basictex

  # Librerie
  sudo tlmgr update --self
  sudo tlmgr install latexmk
  sudo tlmgr install tocbibind
  sudo tlmgr install titlesec
```

### Compilazione

1. Installa l'estensione [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
2. Apri [main.tex](./main.tex) e clicca play (▶︎) in alto a destra
3. Visualizza il PDF cliccando l'icona affianco
