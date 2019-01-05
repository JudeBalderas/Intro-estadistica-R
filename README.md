# Sobre este repositorio

En este repositorio podrán encontrar todo el material que utilizaremos en el curso. Se irá actualizando constanemente y podrán descargarlo si así lo desean o clonarlo por metio de *GitHub*.

## Objetivo del curso

El presente curso tiene como objetivo dar una introducción a herramientas básicas de interpretación, análisis y tratamiento de información, así como de elementos técnicos para el uso de herramientas estadísticas.

El curso estará basado en el lenguaje `R` y versará en el uso de este lenguaje, aplicaciones estadísticas de éste y la creación de reportes profesionales.

## ¿ Cómo instalo (y uso) `R`?

Para este curso vamos a trabajar, desde el principio, con código en `R`. Es necesario tener **la última versión** de este lenguaje, al momento de escribir este repositorio ésta es la versión **3.5.2**.

Para instalarlo, es necesario entrar a [*The Comprehensive R Archive Network*](https://cran.r-project.org/) y seguir las instrucciones para cada sistema operativo.

### MAC OSX

- Basta con descargar el archivo `.pkg` [de este link](https://cran.r-project.org/bin/macosx/R-3.5.2.pkg), descomprimir el archivo, abrir el archivo y seguir las instrucciones.

### Windows

- Basta con descargar el archivo `.exe` [de este link](https://cran.r-project.org/bin/windows/base/R-3.5.2-win.exe), abrir el archivo y seguir las instrucciones.

### Linux

En Terminal, escribir las siguientes dos líneas:

`sudo apt-get update`

`sudo apt-get install r-base`

## ¿Cómo instalar RStudio?

Para instalar RStudio (plataforma que usaremos para el uso de `R`), es necesario acudir a [esta página](https://www.rstudio.com/products/rstudio/download/) y seleccionar nuestro sistema operativo en el menú *Installers for Supported Platforms*. En el caso de Windows, [este](https://download1.rstudio.org/RStudio-1.1.463.exe) es el archivo, y en el caso de MAC OSX el archivo es [éste](https://download1.rstudio.org/RStudio-1.1.463.dmg).

Para Ubuntu, hay que correr estas líneas en Terminal:

`sudo apt-get install gdebi-core`

`wget https://download2.rstudio.org/rstudio-server-1.1.463-amd64.deb`

`sudo gdebi rstudio-server-1.1.463-amd64.deb`

## ¿Cómo instalo LaTeX?

Es importante tener LaTeX para crear documentos en PDF. Para instalarlo, hay que entrar a [este sitio](https://www.latex-project.org/get/) y seleccionar nuestro sistema operativo. Para MAC OSX [este](http://tug.org/cgi-bin/mactex-download/MacTeX.pkg) es el archivo a instalar, para Windows es [éste](https://miktex.org/download/ctan/systems/win32/miktex/setup/windows-x64/basic-miktex-2.9.6942-x64.exe) y para Ubuntu hay que seguir [estos pasos](http://tipsonubuntu.com/2016/09/16/install-tex-live-2016-ubuntu-16-04-14-04/).


## Textos, libros y materiales

### Para aprender R

Hay, realmente, miles de materiales excelentes para aprender `R`. En mi experiencia éstos han sido los más útiles.

- [**Wickham y Grolemund** - R for Data Science](https://r4ds.had.co.nz/): Este el libro sagrado de los que usamos `R` a través del `tidyverse`. Es el mejor y más completo libro para aprender a usar en lenguaje. Les recomiendo mucho terminarlo.

- [Phillips - YaRrr! The Pirate’s Guide to R](https://ndphillips.github.io/piratesguide.html): Una guía introductoria (y bastante divertida) de aprender R. Altamente recomendable también para aprender métodos bayesianos. Yo aprendí `R` con este manual. Phillips también tiene gran material introductorio [en su canal de YouTube](https://www.youtube.com/watch?v=Vkv7-nw3wwU&list=PL9tt3I41HFS9gmeZFEuNrnu_7V_NFngfJ)
  
- [Burns - R's Inferno](https://www.burns-stat.com/pages/Tutor/R_inferno.pdf): La premisa del autor es simple "si están usando R y piensas que es un infierno, este libro es para ti".

- [Sebastián Garrido - Recursos para R](http://segasi.com.mx/cursos/recursos_r/recursos/index.html): "Segasi" ha recolectado un montón de recursos introductorios (y no tanto) en su página personal.

- [Privé - Advanced R Course](https://privefl.github.io/advr38book/index.html):Un buen libro avanzado sobre el tema.

#### RMarkdown y otras herramientas

En este curso se pretende que podamos presentar resultados en reportes profesionales y muy elegantes que puean ser leídos (y usados) por cualquiera. Así, usaremos *Markdown* "con sabor" a `R` para generar código y resultados.

- [Xie, Allaire & Grolemund - R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/): La Guía definitiva para usar *Markdown* "con sabor" a R.
  
- [A simple guide to LaTeX - Step by Step](https://www.latex-tutorial.com/tutorials/): Si bien no usaremos *LaTeX* directamente, sí es importante tenerlo instalado y conocer su existencia y su sintaxis básica para usarla en *RMarkdown*.

### Para estadística en R

Este curso está construido con base en siguientes materiales:

- [James, et al. -  An Introduction to Statistical Learning with Applications in R](https://www-bcf.usc.edu/~gareth/ISL/). El PDF y el código se encuentran en el link.

- [Bruce & Bruce - Practical Statistics for Data Scientists 50 Essential Concepts](http://shop.oreilly.com/product/0636920048992.do): El código de este libro se encuentra en [este repositorio](https://github.com/andrewgbruce/statistics-for-data-scientists/tree/master/src).

- [Hastie, et al. - The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/). El PDF y el código se encuentran en el link.
  
## Repositorios de bases de datos

Algunos repositorios recomendados para buscar buenas bases de datos.

- [Las bases de datos del programa de competencias *Kaggle*](https://www.kaggle.com/datasets)
- [Harvard Dataverse](https://dataverse.harvard.edu/)
- [Datos abiertos del Gobierno Federal](https://datos.gob.mx/)
- [Google Dataset Search](https://toolbox.google.com/datasetsearch)
- [Open ICPSR](https://www.openicpsr.org/openicpsr/)
- [UK Data Service](http://reshare.ukdataservice.ac.uk/)

## Calendario de sesiones

- Sesión 1
  - Presentación
  - Datos
  
- Sesión 2
  - Presentación
  - Datos
  
- Sesión 3
  - Presentación
  - Datos
  
- Sesión 4
  - Presentación
  - Datos
  