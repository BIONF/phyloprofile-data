# BUSCO Arthropoda Demo Data for [PhyloProfile Tool](https://github.com/BIONF/PhyloProfile)

## Description
This folder contains phylogenetic profile data for BUSCO Arthropoda proteins. Two additional layers of information integrated to this data is the *forward* and *backward* **protein domain architecture similarity**.

*Domain architecture similarity* scores are used to compare the protein architecture between seed and its ortholog ([Koestler et al. (2010), BMC Bioinformatics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2931517/)). Forward scores indicate the comparison where the domain architectures of seed proteins are used as reference (i.e. missing domains in seed proteins will be penalized). While backward scores are obtained when orthologous proteins are used as reference (i.e. missing domains in orthologs will be penalized).

## Content
- **Main input file** (phylogenetic profile integrated with forward and backward domain similarity scores): `arthropoda.phyloprofile`

- Optional **Domain files**: *too large for uploading!!!*

- Optional **FASTA sequence file**:  `arthropoda.extended.fa`. _You can input this file into `FASTA config` -> `Choose location for: Concatenated fasta file`_.

### Different input formats are described in our [Input-Data Wiki Page](https://github.com/BIONF/PhyloProfile/wiki/Input-Data).
