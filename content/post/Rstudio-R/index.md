---
authors:
- admin
categories: []
date: "2019-02-05T00:00:00Z"
draft: false
featured: true
image:
  caption: ""
  focal_point: ""
projects: []
subtitle: Guia básico de R, RStudio e RMarkdown
summary: Guia básico de R, RStudio e RMarkdown
tags: []
title: Introdução e ferramentas de trabalho 
---





<!--![png](https://www.r-project.org/Rlogo.png)-->

# Ferramentas básicas utilizadas na construção deste site/blog

Faz muitos anos venho trabalhando num único ambiente integrado ([RStudio](https://rstudio.com/products/rstudio/)) que me ajuda nos diversos desafíos encontrados na carreira de cientista, desde o básico como fazer um teste estatístico, como fazer um artigo reprodutível com foco em ciencia de dados, capítulos inteiros de uma tese de doutorado e incluso este site, que está sendo feito desde o RStudio/[Hugo](https://github.com/wowchemy/wowchemy-hugo-modules).


Ferramentas básicas:


1. [R](https://www.r-project.org) é a base de tudo o meu trabalho, R é um ambiente de software **livre** para computação estatística.

2. O IDE [RStudio](https://rstudio.com/products/rstudio/) é um conjunto de ferramentas integradas projetadas para ajudar a ser mais produtivo com R e Python. Inclui um console, um editor que oferece suporte à execução direta de código e uma variedade de ferramentas robustas para graficar, depurar e gerenciar o espaço de trabalho.

3. O [R Markdown](https://rmarkdown.rstudio.com/lesson-1.html) fornece uma estrutura para autores em ciência de dados. Num único arquivo R Markdown é possível salvar e executar código assim gerar relatórios de alta qualidade que podem ser compartilhados com um público em diversos formatos.R Markdown é uma variante do [Markdown](https://daringfireball.net/projects/markdown/) que tem blocos de código R incorporados, para serem usados com o [knitr](https://yihui.org/knitr/) para facilitar a criação de relatórios reproduzíveis baseados na web. A sintaxe Markdown tem alguns aprimoramentos; por exemplo, você pode incluir equações $\LaTeX{}$.

4. O [ggplot2](https://ggplot2.tidyverse.org) é um sistema para a criação declarativa de gráficos, baseado na _Gramática dos Gráficos_. É difícil descrever como o ggplot2 funciona porque ele incorpora uma profunda filosofia da visualização, porém é uma das ferramentas mais interessantes para geração de gráficos complexos. No ggplot você fornece os dados, diz ao ggplot2 como mapear as variáveis para a estética, qual base gráfica utilizar e então adiciona camadas, escalas, especificações de facetas e sistemas de coordenadas. O ggplot2 faz parte do [tidyverse](https://www.tidyverse.org) que é uma coleção de pacotes do R projetados para ciência de dados. Todos os pacotes compartilham uma filosofia de design, gramática e estruturas de dados subjacentes.








# Introdução ao R!


## Instalar R 

[Instalar R](https://www.anaconda.com/distribution/#download-section) which includes Python 3 and Jupyter notebook.

Otherwise, for advanced users, install Jupyter notebook with `pip3 install jupyter`.

## Create a new blog post 

Introduction
Overview
R Markdown provides an authoring framework for data science. You can use a single R Markdown file to both

save and execute code
generate high quality reports that can be shared with an audience
R Markdown documents are fully reproducible and support dozens of static and dynamic output formats. This 1-minute video provides a quick tour of what’s possible with R Markdown:


Installation
Like the rest of R, R Markdown is free and open source. You can install the R Markdown package from CRAN with:

install.packages("rmarkdown")
Get Started
The links to the left provide a quick tour of R Markdown. The links at the top provide examples of R Markdown documents, as well as an in depth discussion of various R Markdown topics.

You may also find the following resources helpful:

The R Markdown Cheatsheet
The R Markdown Reference Guide
Continue to How It Works