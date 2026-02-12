# Инструкция по сборке в linux

## Установка зависимостей
```
sudo apt update
sudo apt install texlive-xetex texlive-lang-cyrillic texlive-science texlive-latex-extra latexmk
```
## Сборка
```sh
latexmk -xelatex main.tex
```
