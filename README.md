
## This is a Training notebook, the intention is to keep up to date with analysis techniques and tools. 
# Spatial Transcriptomics Analyses of Mouse Brain: 10x Genomics Xenium In Situ
Spatial Transcriptomics is a groundbreaking technique that combines RNA sequencing with spatial localization to map gene expression within intact tissues. Unlike traditional RNA-seq, which provides a bulk measurement of gene activity, spatial transcriptomics preserves the anatomical context, allowing researchers to examine where specific genes are expressed within the tissue architecture. By correlating gene expression data with histological features, this technique offers unprecedented insight into cellular heterogeneity, tissue organization, and the interactions between different cell types within their native environments.

# Projects and Select Sample Outputs (full output can be found in notebooks)
This analysis explores subcellular-resolution spatial transcriptomics data from fresh-frozen mouse brain tissue using the 10x Genomics Xenium platform. The dataset captures single-cell gene expression patterns with precise spatial coordinates, enabling visualization of cortical layer organization through marker genes (Cux2, Rorb, Bcl11b, Foxp2) and identification of distinct cell populations including excitatory neurons, inhibitory interneuron subtypes (GABAergic, somatostatin+, parvalbumin+), and glial cells. Through unsupervised clustering and spatial mapping, we characterize cellular heterogeneity and tissue architecture at unprecedented resolution, demonstrating the power of in situ transcriptomics for understanding brain organization.


<img width="400" height="400" alt="output" src="https://github.com/user-attachments/assets/bca6afcc-6ebd-4520-adf0-20e339d5defe" />

Violin plots displaying the distribution of detected features and total counts per cell with individual cell observations overlaid.

<img width="400" height="400" alt="output2" src="https://github.com/user-attachments/assets/f0d3be62-9de0-4c4c-a574-29310601071f" />

Spatial visualization of inhibitory neuron markers (Gad1, Sst, Pvalb) and astrocyte marker (Gfap) across the tissue section, showing regional expression patterns.

<img width="400" height="400" alt="output4" src="https://github.com/user-attachments/assets/b6230492-5251-4811-ad6f-4582c45d7f22" />

High-resolution view of cellular segmentation boundaries overlaid with inhibitory neuron markers (Gad1, Sst, Npy2r, Pvalb, Nrn1), demonstrating single-cell resolution.

<img width="400" height="400" alt="output5" src="https://github.com/user-attachments/assets/d8e3546c-ed75-43ad-b46d-14bdc8ca76dc" />

UMAP dimensionality reduction showing distinct cell type clusters identified through unsupervised clustering at 0.3 resolution.

<img width="400" height="400" alt="output6" src="https://github.com/user-attachments/assets/331e9e8d-1c84-40b3-8970-8fa4d93033b1" />

Spatial mapping of identified clusters onto tissue coordinates, revealing anatomical organization of cell populations.
