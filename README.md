# Machine Learning in Computational Biology – Project Repository

## Scope of the Project
This repository contains the code and data to reproduce the analysis and results from the project report **“Power Analysis of Single Cell RNA-Sequencing Experiments”** (MARS-seq protocol). We re-process publicly available MARS-seq single-cell RNA-seq data to improve sensitivity and accuracy metrics through a standardized UMI-preserving pipeline, and systematically explore the effect of downsampling to different sequencing depths.

## Dataset Used
- **GEO Accession:** GSE54006  
- **Data Type:** UMI-based single-cell gene expression matrix for MARS-seq  
- **ERCC Spike-in Concentrations:** `Supplementary_Table_2.csv` (from Svensson et al. Power Analysis paper)

## Reproducing the Results

1. **Clone the project repository**  
   ```bash
   git clone https://github.com/maria-defteraiou/MLCB_project.git

2. **Navigate into the directory and install dependencies**
    ```bash
    cd MLCB_project
    pip install -r requirements.txt

3. **Ensure the ERCC concentration file is in place**

4. **Launch the Jupyter notebook pipeline**
   ```bash
   jupyter notebook pipeline_analysis.ipynb

5. **Run all cells**



   
