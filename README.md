# Evan's SNP Genotyping Data

_My sample is currently being shipped to and analyzed by the lab. This repository will be updated once my data is made available to me._

## Introduction

The data in this repository contains around [1 million](http://snpedia.com/index.php?title=Category:On_chip_23andMe_v3) genetic markers called [single-nucleotide polymorphisms](http://en.wikipedia.org/wiki/Single-nucleotide_polymorphism) (SNPs). These SNPs identify various information such as disease risk/resistance/carrier status, drug responses, and various traits including eye color, hair color, lactose intolerance, and much more.

This data was collected by [23andMe](https://www.23andme.com/) in a CLIA-certified laboratory using a modified Illumina OmniExpress+ bead array (BeadChip).

## Data Format

The data is a tab-separated file. Each line corresponds to a single SNP and contains four fields:

* **rsid** — The SNP identifier (either the RSID or an internal 23andMe identifier)
* **chromosome** and **position** — The location of the SNP on the reference human genome.
* **genotype** — The genotype call oriented with respect to the plus strand on the human reference sequence.

In the current version of the data, SNP positions are reported using the [NCBI Build 37 (also known as Annotation Release 104)](http://www.ncbi.nlm.nih.gov/mapview/map_search.cgi?taxid=9606) genome assembly. It's possible the data may be updated periodically due to ongoing improvements in 23andMe's ability to call genotypes.

## Why?

For science!

Following in the steps of [Manu Sporny](http://manu.sporny.org/2011/public-domain-genome/), I'm releasing my genetic data from 23andMe. I admire what he's done, what he stands for, and the insightful discussions that he's provoked. Additionally I intend to provide this data to the [Personal Genome Project](http://www.personalgenomes.org/) to help advance their research in personal genetics.

## License & Use

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Evan Coury has waived all copyright and related or neighboring rights to Evan Coury's Genetic Data from 23andme.com. This work is published from: United States. 

_Please note that the Genetic Information Nondiscrimination Act forbids the use of this information by employers and health insurance companies for employment and coverage issues._
