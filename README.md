# Econoalgoritmia: Econometría avanzada y ciencia de datos con R

<br/>
<br/>

<p align="center"><img align="center" src="https://github.com/Jeshua-Romero-Guadarrama/Econoalgoritmia/blob/main/images/Econoalgoritmia.png" width="30%" height="30%"></p>

<br/>
<br/>

## 📖 Sobre el curso

<p><img src="https://github.com/Jeshua-Romero-Guadarrama/Econoalgoritmia/blob/main/images/logo.png" alt="logo" align="right" width="20%" height="20%"> 
Los estudiantes con poca experiencia en estadística y econometría a menudo tienen dificultades para entender los beneficios de desarrollar habilidades de programación al momento de aplicar diversos métodos econométricos. </i>Econoalgoritmia: Econometría avanzada y ciencia de datos con R</i>  por Jeshua Romero Guadarrama (2021), ofrece una introducción interactiva a los aspectos esenciales de la programación por medio del lenguaje y software estadístico R, así como una guía para la aplicación de la teoría económica y econométrica en entornos específicos. En otras palabras, el objetivo es que los estudiantes se adentren al mundo de la economía aplicada mediante ejemplos empíricos presentados en la vida diaria y haciendo uso de las habilidades de programación recién adquiridas. Dicho objetivo se encuentra respaldado por ejercicios de programación interactivos generados con DataCamp Light y la incorporación de visualizaciones dinámicas de conceptos fundamentales mediante la flexibilidad de JavaScript, a través de la biblioteca D3.js.</p>

El curso se puede consultar aquí: [Econoalgoritmia: Econometría avanzada y ciencia de datos con R](https://jeshua-romero-guadarrama.github.io/Econoalgoritmia/)

<br/>
<br/>

## ✍🏻 Referencia bibliográfica

Romero, G. J. (2021). *Econoalgoritmia: Econometría avanzada y ciencia de datos con R*. JeshuaNomics.

<br/>
<br/>

## 📦 Paquetería necesaria

Para ejecutar los ejemplos mostrados en el libro será necesario tener instalados los siguientes paquetes:

[`lattice`](https://cran.r-project.org/web/packages/lattice/index.html), 
[`ggplot2`](https://cran.r-project.org/web/packages/ggplot2/index.html), 
[`foreign`](https://cran.r-project.org/web/packages/foreign/index.html), 
[`car`](https://cran.r-project.org/web/packages/car/index.html), 
[`leaps`](https://cran.r-project.org/web/packages/leaps/index.html), 
[`MASS`](https://cran.r-project.org/web/packages/MASS/index.html), 
[`RcmdrMisc`](https://cran.r-project.org/web/packages/RcmdrMisc/index.html), 
[`lmtest`](https://cran.r-project.org/web/packages/lmtest/index.html), 
[`glmnet`](https://cran.r-project.org/web/packages/glmnet/index.html), 
[`mgcv`](https://cran.r-project.org/web/packages/mgcv/index.html), 
[`rmarkdown`](https://cran.r-project.org/web/packages/rmarkdown/index.html), 
[`knitr`](https://cran.r-project.org/web/packages/knitr/index.html) y 
[`dplyr`](https://cran.r-project.org/web/packages/dplyr/index.html).

Por ejemplo, ejecutando el siguiente comando:

```{r eval=FALSE}
pkgs <- c("lattice", "ggplot2", "foreign", "car", "leaps", "MASS", "RcmdrMisc", 
          "lmtest", "glmnet", "mgcv", "rmarkdown", "knitr", "dplyr",
          "caret", "rattle", "car", "AppliedPredictiveModeling", "ISLR")

install.packages(setdiff(pkgs, installed.packages()[,"Package"]), dependencies = TRUE)
```

___

<p align="center"><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc-sa.eu.svg"/></a></p>Esta obra está autorizada bajo la <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.