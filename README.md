# README

## Objective

In our comparative studies of the 30 assigned samples, we conducted genomic comparison and phylogenetics analysis to infer relatedness. Comparative genomics is a robust scientific approach that involves comparing the genetic content of multiple organisms to understand their evolutionary relationships, identify genetic variations, and elucidate functional capabilities. In the context of pathogen outbreak investigation, comparative genomics can reveal how specific strains differ from each other and from known reference genomes, which is crucial for pinpointing the outbreak source and understanding the pathogen’s evolution. For doing comparative genomics analysis, we have built a pipeline that utilizes three key tools for comparative genomics: 

## Tools Used in the Pipeline

1. **gsearch**: This tool is used to perform advanced genomic searches and comparisons using MinHash-like signatures and Hnsw (Hierarchical Navigable Small World) graphs.
2. **parsnp**: This tool is used for phylogenetic reconstruction and identifying core genome single nucleotide polymorphisms (SNPs).
3. **roary**: This tool is used for pangenome analysis, identifying the core and accessory genes across multiple genomes.
4. **amrfinder**: This tool is used for identifying antimicrobial resistance genes, providing crucial data for understanding resistance mechanisms and guiding treatment options. Group 2 had already used this software so we have just used the results from them.

These tools work together to provide a comprehensive analysis of the genomic data, from pangenome analysis to phylogenetic reconstruction.

## Links to Software

- [gsearch GitHub Repository](https://github.com/jean-pierreBoth/gsearch)
- [parsnp GitHub Repository](https://github.com/marbl/parsnp)
- [roary GitHub Repository](https://github.com/sanger-pathogens/Roary)
- [amrfinder GitHub Repository](https://github.com/ncbi/amr)
