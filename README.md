# UTC-UV

Des cheatsheets à utiliser pour les révisions ou à imprimer si autorisé par l'enseignant.

## Comment contribuer ?

Forkez le projet, ajouter une matière ou améliorez/corrigez une cheatsheet, puis faites un pull request (avec une description détaillée si possible).  
Si vous souhaitez ajouter une matière, il y a un template à reprendre, disponible dans ```/template```.

## À propos de LaTeX

### Installer LaTeX sur Linux

```bash
sudo apt-get update
sudo apt-get install texlive-full
```

### Comment compiler une cheatsheet

```bash
cd LO21 # Par exemple
pdflatex LO21-cheatsheet # Ne pas écrire l'extention .tex
pdflatex LO21-cheatsheet # Lancer la même commande deux fois est important pour les références, etc.
```