# pymitoqc

Python implementation of low-quality or compromised cell QC filtering adapted from the miQC R package [see here](https://www.bioconductor.org/packages/release/bioc/html/miQC.html)

Implemented here is a bayesian gaussian mixture model to find cells with a combination of 1. high mitochondrial content and 2. low number of detected genes.

See publication for more details: Hippen AA, Falco MM, Weber LM, Erkan EP, Zhang K, Doherty JA, Vähärautio A, Greene CS, Hicks SC. miQC: An adaptive probabilistic framework for quality control of single-cell RNA-sequencing data. PLoS Comput Biol. 2021 Aug 24;17(8):e1009290. doi: 10.1371/journal.pcbi.1009290. PMID: 34428202; PMCID: PMC8415599.

