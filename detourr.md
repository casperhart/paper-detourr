---
title: "detourr: An R Package extending {tourr} with {HTMLWidgets}"
abstract: >
  An abstract of less than 150 words.
draft: true
author:  
  - name: Casper Hart 
    affiliation: University of Auckland 
    address: Department of Statistics 
    email: casperhart93@gmail.com 
  - name: Earo Wang 
    email: earo.wang@auckland.ac.nz 
    affiliation: University of Auckland
    address: Department of Statistics 
type: package
output: 
  rjtools::rjournal_web_article
bibliography: detourr.bib

---



# Introduction

Interactive data graphics provides plots that allow users to interact them. One of the most basic types of interaction is through tooltips, where users are provided additional information about elements in the plot by moving the cursor over the plot.

This paper will first review some R packages on interactive graphics and their tooltip implementations. A new package \CRANpkg{ToOoOlTiPs} that provides customized tooltips for plot, is introduced. Some example plots will then be given to showcase how these tooltips help users to better read the graphics. 

# Background

Some packages on interactive graphics include \CRANpkg{plotly} [@plotly] that interfaces with Javascript for web-based interactive graphics, \CRANpkg{crosstalk} [@crosstalk] that specializes cross-linking elements across individual graphics.  The recent R Journal paper \CRANpkg{tsibbletalk} [@RJ-2021-050] provides a good example of including interactive graphics into an article for the journal. It has both a set of linked plots, and also an animated gif example, illustrating linking between time series plots and feature summaries.

# Customizing tooltip design with \pkg{ToOoOlTiPs}

\pkg{ToOoOlTiPs} is a packages for customizing tooltips in interactive graphics, it features these possibilities.

# A gallery of tooltips examples

The \CRANpkg{palmerpenguins} data [@palmerpenguins]  features three penguin species which has a lovely illustration by Alison Horst in Figure \@ref(fig:penguins-alison). 

<img src="penguins.png" title="Artwork by \@allison\_horst" alt="Artwork by \@allison\_horst" width="100%" height="30%" />

Table \@ref(tab:penguins-tab-static) prints at the first five rows of this data:





Figure \@ref(fig:penguins-ggplot) shows an  plot of the penguins data, made using the \CRANpkg{ggplot2} package. 





# Summary

We have displayed various tooltips that are available in the package \pkg{ToOoOlTiPs}. 
