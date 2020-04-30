# baza-podatkov-fakultete
Projekti OPB

---
output:
  html_document: default
  pdf_document:
    includes:
      in_header: lib/styles.sty
    latex_engine: xelatex
runtime: shiny

---
```
{r setup, echo=FALSE, results='hide', message=FALSE, warning=FALSE}
source('lib/libraries.r', encoding='UTF-8')
Sys.setlocale('LC_ALL', 'Slovenian')
```
```
{r studio, echo=FALSE, results='asis'}
source('lib/rstudio.r', encoding='UTF-8')
```


<center>
![](slike/ER_diagram_projekta.png)
</center>

