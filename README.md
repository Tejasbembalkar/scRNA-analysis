# scRNA-analysis

Single cell RNA sequencing (scRNA-seq) is a novel technique for extracting more detailed information from genome. Technically, scRNA-seq includes two parts of experimental design and data analysis. As it was mentioned before, scRNA-seq is useful in case of heterogeniety of cells and developmental studies. For example, imagine brain tissue with tens of cell types with tens of different expression profiles. For extracting transcriptome of each cell, it is necessary to isolate each cell from the tissue properly.
scRNA-Seq Computational Workflow

scRNA-seq raw data includes reads with cell barcode and UMIs. Before alignment of reads to genome, reads can be grouped using cell barcodes and the frequency of each read is estimated per cell per gene using UMIs. After alignment and frequency calculations, we have a gene expression table containing cells represented in the columns and genes represented in the rows. This is what we analyze in scRNA-seq comlutational workflow.
Here You can see the bioinformatics workflow for analysis of scRNA-seq data.

Workflow image
![image](https://github.com/Tejasbembalkar/scRNA-analysis/assets/133912637/d40c7ccb-c890-4f12-ac3d-b132007a58e6)
