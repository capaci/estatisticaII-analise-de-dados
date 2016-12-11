# Trabalho de Estatística II da UFPR
Trabalho de CE003, semestre 2016-2, que consiste em fazer uma análise estatística de alguns dados. Os dados escolhidos para esse trabalho em questão foram os dados da tabela <em>studentdata</em>, do pacote LearnBayes do programa R. O relatório é todo escrito em LaTeX, utilizando o pacote <em>Sweave</em> para executar trechos de código R presentes no documento, o que facilita a escrita do relatório.


#### Arquivos:

- **comousarosbagui.pdf**: arquivo que contém algumas informações e comandos interessantes sobre o Sweave
- **relatorio.Rnw**: arquivo que contém todo o LaTeX escrito para gerar o pdf do relatório. Ele se encontra no formato ".Rnw", pois é o formato necessário para o Sweave poder interpretar os trechos de código R que estão no documento.
- **studentdata.txt**: arquivo que contém os dados utilizados para toda a análise que foi feita no trabalho

## Getting Started
As informações necessárias para compilar o LaTeX, estão logo abaixo:

### Instalar o LaTeX
```
sudo apt-get install texlive texlive-latex-extra texlive-lang-portuguese
```

### Instalar o R
```
sudo apt-get install r-base
```

### Instalar o RStudio (opcional, mas facilita bastante)
[Link para download](https://www.rstudio.com/products/rstudio/download3/)

## Compilando
##### Pelo terminal:
```
R CMD Sweave relatorio.Rnw
pdflatex relatorio.tex
```

##### Pelo RStudio:
É bem intuitivo, na verdade. Para facilitar o entendimento, é interessante assistir esse [vídeo](http://cdn.screenr.com/video/8352c25b-7324-4134-970b-b7c427381adb.mp4) que, apesar de ser do Knitr, software semelhante ao Sweave, mostra um pouquinho sobre algumas funcionalidades interessantes do RStudio, o suficiente para esse trabalho.  

## Materiais auxiliares
- [Introdução à R](http://leg.ufpr.br/~paulojus/embrapa/Rembrapa/Rembrapa.pdf)
- [O que é, por que e como usar Sweave](http://www.leg.ufpr.br/~paulojus/embrapa/Rembrapa/Rembrapase35.html)
