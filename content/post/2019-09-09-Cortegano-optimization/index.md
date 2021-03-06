---
title: 'New paper out: Optimal management of genetic diversity in subdivided  populations'
author: anpefi
date: '2019-09-13'
slug: 2019-09-13-Cortegano-optimization
categories: []
tags:
  - Conservation genetics
  - Metapop
  - paper
  - Genetic diversity
  - Animal breeding
subtitle: ''
summary: ''
authors: []
lastmod: ''
featured: no
draft: false
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

A new paper, in which I have collaborated, has been published today with the following reference López-Cortegano, E., Pouso, R., Labrador, A., Pérez-Figueroa, A., Fernández, J., Caballero, A. (2019). [Optimal management of genetic diversity in subdivided populations](https://www.frontiersin.org/articles/10.3389/fgene.2019.00843). Frontiers in Genetics, 10:843.

The objective in this study is to examine the consequences of choosing a conservation strategy based on maximizing either heterozygosity or allelic diversity of SNP haplotypes in a subdivided population. This kind of study was already done for a single, undivided population [(Fernández et al. 2004)](https://conbio.onlinelibrary.wiley.com/doi/full/10.1111/j.1523-1739.2004.00341.x) resulting that each maximization method was, as would be expected, more efficient in maintaining each corresponding diversity measure. However, maximization of heterozygosity was able to maintain levels of allelic diversity almost as high as the method specifically devoted to that task. Those results were carried out in the context of a single undivided population.But most populations in nature and in conservation programs (zoos, germplasm collections, botanic gardens, etc.) are subdivided and this subdivision could have a big impact on how these optimization methods work.

Here, we address this issue by performing simulations of a subdivided population and a conservation program where maximization of heterozygosity and allelic diversity are carried out for two sets of genetic markers, one representing a small number of known loci where diversity should be preserved and another aimed to perform whole-genome management. The pipeline required to simulate all populations assayed as well as to run the corresponding population analyses and managementsimulations is available in [https://gitlab.com/elcortegano/hadopt](https://gitlab.com/elcortegano/hadopt).

Our results suggest that maximization of allelic diversity can be more efficient in maintaining the genetic diversity of subdivided populations than maximization of expected heterozygosity because the former maintains a larger number of alleles while making a better control of inbreeding. Thus, maximization of allelic diversity should be a recommended strategy in conservation programs for structured populations.

This is a quite old work that a student, Adriana Labrador, started as a master thesis that I have co-directed in 2012 (science is sometimes very slow.) That preliminary work was later continued by another student, Ramón Pouso, in his undergraduate thesis, which I also co-directed, in 2014. The results were interesting but there was still a lot of work to do to to obtain solid conclusions, but just then I left Armando Caballero's lab and my time for this type of collateral projects decreased drastically. Thus, the subject was parked for a couple of years, until Eugenio López-Cortegano arrived at Caballero's lab as a postdoc, taking care of old tasks that I had left pending, such as the improvement of the software [metapop2](https://doi.org/10.1111/1755-0998.13015) or this study (that heavely rely on the use of metapop). Eugenio did a good job that resulted both tasks have respective publications this year, successfully completing tasks that were left pending and to which I could hardly devote time enough to them. 
