# ExperimentalLinguistics
Reproducible code and data for the chapter New Directions in Statistical Analysis for Experimental Linguistics

The directory structure is

      .
      ├── ExperimentalLinguisticsVasishth.Rnw
      ├── ExperimentalLinguisticsVasishth.pdf
      ├── Nicenboim2018CogSci.Rda
      ├── bibcleaned.bib
      ├── README.md
      ├── figure
      │   ├── unnamed-chunk-11-1.pdf
      │   ├── unnamed-chunk-13-1.pd
      │   ├── unnamed-chunk-6-1.pdf

The main file is ExperimentalLinguisticsVasishth.Rnw. You will find the R code embedded inside this file. The compiled version of this document is the pdf file. The .bib file has references used in the paper.  Compiling the Rnw file can be done within RStudio by pressing the compile pdf button. Once the Rnw file is compiled (it will take a while), a .tex file is created. You may need to run latex on the resulting .tex file: on the command line, type

latex ExperimentalLinguisticsVasishth
bibtex ExperimentalLinguisticsVasishth
latex ExperimentalLinguisticsVasishth
latex ExperimentalLinguisticsVasishth

The data are in the file Nicenboim2018CogSci.Rda.

The figures directory contains the figures in the paper.
