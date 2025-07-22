# Gene_Expression_Analysis using single cell RNA sequencing method
This project performs a basic single-cell RNA-seq (scRNA-seq) analysis using Python and the Scanpy library. It includes steps for preprocessing, clustering, visualization, and marker gene detection.

# Dataset 
We will be using the sample dataset from 10x Genomics
[pbmc3k_filtered_gene_bc_matrices.tar.gz](https://github.com/user-attachments/files/21371985/pbmc3k_filtered_gene_bc_matrices.tar.gz)

Unzip this file after download and put it inside your working directory. Can be renamed.

# Running the workflow
## Step 1: Install required packages
To do this you can just download the requirements.txt file and run
```
pip install -r Req.txt
```
## Step 2: Run the analysis
```
python script.py
```

# Workflow steps overview
- load the data
- Filter it
- Perform Normalization
- PCA and UMAP for clustering
- Differentially expressed genes

# Plots for visualization
- PCA plots
- Heatmap
- UMAP clusters
- Volcano plot

  # Written by:
  Rojina Sapkota



