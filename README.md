# Bayesian Network Compendium
![renderbook](https://github.com/matteodelucchi/bncompendium/workflows/renderbook/badge.svg)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


A knowledge collection about Bayesian Network statistics and its relatives.  
Published on [matteodelucchi.github.io/bncompendium/](https://matteodelucchi.github.io/bncompendium/)

# How to use?
You can read the [latest version online](https://matteodelucchi.github.io/bncompendium/) or downloaded as [pdf](https://matteodelucchi.github.io/bncompendium/bncompendium.pdf).

# How to contribute?
This book is based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). Please see the page "Get Started" at https://bookdown.org/home/about/ for examples and the package structure.

## Getting started
0. Install the R packages: 
```
install.packages("bookdown)
install.packages("devtools")
```  
1. Fork the [repository](https://github.com/matteodelucchi/bncompendium).
2. Install your fork of the R package ```bncompendium```:
```
devtools::install_github('https://github.com/<yourusername>/bncompendium')
```
3. Test your installation with a live preview
```
bookdown::serve_book(preview = FALSE)
```

## Found a mistake, error or typo?
Open an [issue](https://github.com/matteodelucchi/bncompendium/issues). 

## Want to contribute?
1. Follow [the getting started instructions](##getting-started).
2. Add text, corrections etc. Check if there is a topic on the [wishlist](https://github.com/matteodelucchi/bncompendium/labels/santa%20claus) that you would like to write about.
3. Check if it runs locally.
```
bookdown::serve_book(preview = FALSE)
```
4. Create a pull request (reference issues if necessary). 

## Want to have a sepcific topic covered?
Open an [issue](https://github.com/matteodelucchi/bncompendium/issues) with the label [santa clause](https://github.com/matteodelucchi/bncompendium/labels/santa%20claus) and explain the topic shortly.

# Licence
<p xmlns:dct="http://purl.org/dc/terms/" xmlns:cc="http://creativecommons.org/ns#" class="license-text"><a rel="cc:attributionURL" property="dct:title" href="https://github.com/matteodelucchi/bncompendium">Bayesian Network Compendium</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/matteodelucchi/">Matteo Delucchi</a> is licensed under <a rel="license" href="https://creativecommons.org/licenses/by/4.0">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" /></a></p>

