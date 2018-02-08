# Test Data for [PhyloProfile Tool](https://github.com/BIONF/PhyloProfile)

This folder contains phylogenetic profile data for AMPK-TOR pathway, which is based on the work of [Roustan et. al (2016)](https://doi.org/10.1093/jxb/erw211).

_*.phyloprofile_ are main input files.

Use *domains_B* or *domains_F* file depending on the direction of the protein architecture comparison (F for forward, i.e. missing domains in seed proteins will be penalized; and B for backward. i.e. missing domains in orthologs will be penalized).

For representing FASTA sequences, input *.fa* file into `FASTA config` -> `Choose location for: oneSeq.extended.fa`.
