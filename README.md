# CSIC5011 Final Project of Team Sheep

#### HUANG Xinrui, Zeng Yeqin and GU Yanwu

## Project Description

This is the final project of CSIC 5011, 2025 Spring in the Hong Kong University of Science and Technology, taught by Prof. Yao Yuan. 

The topic of this project is based on the data of  *A single-cell RNA-seq survey of the developmental landscape of the human prefrontal cortex*. This dataset contains a single cell gene expression matrix $X \in \mathbb R^{n\times p}$ of $n = 24153$ genes and $p = 2394$ cells. Each value is in the unit of transcript-per-million (TPM). The file of the dataset is in tab-delimited text format, where each row represents one gene (the first row is the cell ID) and Final Project 9 each column represents one cell (the first column is the gene name). The size is about $33.2$ Mb in gzipped format and about 160 Mb after decompression. Link to download the data:

https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE104276&format=file&file=GSE104276%5Fall%5Fpfc%5F2394%5FUMI%5FTPM%5FNOERCC%2Exls%2Egz

## File Structure 

Below is the structure of the project files and directories, along with their purposes:

- **CSIC5011_Team_Sheep_Poster.pdf**
  The poster of the project.
  
- **CSIC5011_Team_Sheep_Slides.pdf**
  The slides of the project.
  
- **Dimension reduction and subclustering.ipynb**
  This file presents six different topological methods including UMAP, T-SNE, PCA, MDS, ISOMAP, LLE for dimensionality reduction, subtype classification using Louvain algorithm, and visualization related to marker genes.
  
- **Monocle3&Slingshot_analysis.Rmd**
  The code for reproducing trajectory analysis result in FIg. 6&Fig. 7 of poster using Monocle3, Stingshot. (Remark: the interactive mode of Monocle3 may not work in jupyter notebook)
  
- **Monocle_anlysis.ipynb**
  The code for reproducing trajectory analysis result in FIg. 6 of poster using Monocle.


## Appendix

The bilibili link of the video of the project is:

https://www.bilibili.com/video/BV1HdLqzeEGZ/?vd_source=baa4f1b8a9005c554b815e5ba06ca5e5

The Github repository of this project is: 

https://github.com/yanwugu2001/CSIC5011_Final_Project

