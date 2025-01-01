# README: Lung Cancer Single-Cell Transcriptomics Analysis

## **Overview**

This project analyzes single-cell RNA sequencing (scRNA-Seq) data from lung cancer samples, specifically using the **GSE131907** dataset obtained from the Gene Expression Omnibus (GEO). The goal of this analysis is to gain insights into the cellular composition, differential gene expression, and pathway activities within the tumor microenvironment. The pipeline is implemented in R using the Seurat package and focuses on real-world datasets to address critical research questions in lung cancer biology.

---

## **Key Features**
- **Cell Type Identification**: Clustering and annotation of cell types in lung cancer samples.
- **Differential Gene Expression (DEG) Analysis**: Identifies DEGs between tumor and normal tissue samples.
- **Pathway Enrichment Analysis**: Explores enriched pathways for specific cell types to understand biological processes.
- **Interactive Visualizations**: Generates UMAP plots, heatmaps, and pathway barplots for intuitive data representation.

---

## **Project Goals**
1. Characterize the cellular composition of lung cancer tissues.
2. Identify key differentially expressed genes (DEGs) and their implications.
3. Explore tumor microenvironment interactions and pathway activities.

---

## **Requirements**
### **Software and Libraries**
- R (≥4.0.0)
- [Seurat](https://satijalab.org/seurat/)
- dplyr
- ggplot2
- clusterProfiler
- Matrix

### **Data Source**
The project utilizes the **GSE131907** scRNA-Seq dataset from GEO. This dataset can be accessed at the [GEO website](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131907). Download and set the path to the data in the script.

---

## **Pipeline Overview**
1. **Data Acquisition**: Download scRNA-Seq data from the GEO database (GSE131907).
2. **Preprocessing**: Perform quality control, normalization, and filtering.
3. **Clustering and Annotation**: Cluster cells and annotate cell types using known markers.
4. **Differential Expression Analysis**: Identify DEGs between tumor and normal tissues.
5. **Pathway Enrichment**: Analyze biological pathways enriched in specific clusters.
6. **Visualization**: Generate visualizations like UMAP plots, heatmaps, and pathway barplots.

---

## **Usage**
1. Clone this repository:
   ```bash
   git clone https://github.com/username/lung_cancer_scrna_analysis.git
   cd lung_cancer_scrna_analysis
