This folder contains all juputer notebooks to regenerate figures used in the Molecular Therapy paper.
  - <ins>**Molecular_Therapy_Figures.ipynb**</ins>: 
    - Main notebook to renerate all figures used in the paper
  - <ins>**TenX_preanalysis.ipynb**</ins>:
    - Preanalysis of all TenX samples, including concatenating UMI count files and doublet detection
  - <ins>**PBMC_b4BC_analysis.ipynb**</ins>:
    - Analysis of PBMC samples using SCANPY, patient variance was observed so that batch correction was performed
  - <ins>**PBMC_BatchCorrection_R.R**</ins>:
    - Batch correction of PBMC samples using MNNcorrect in R
  - <ins>**PBMC_BC_Analysis.ipynb**</ins>:
    - Analysis of batch correction PBMC samples using SCANPY
  - <ins>**Project_PBMC_onto_PBMC68Kzheng17.ipynb**</ins>:
    - Projection of PBMC samples onto [Zheng2017](https://www.nature.com/articles/ncomms14049) landscape
  - <ins>**Tcells_in_PBMC.ipynb**</ins>:
    - Analysis of T cells in batch corrected PBMC samples using SCANPY
  - <ins>**Tcells_analysis.ipynb**</ins>:
    - Analysis of *in vitro* T cell samples using SCANPY
  - <ins>**Tcells_conST_sep.ipynb**</ins>:
    - Analysis of *in vitro* T cell samples separated by condition (+Antigen/-Antigen) using SCANPY
  - <ins>**Tcells_vecPB_sep.ipynb**</ins>:
    - Analysis of *in vitro* T cell samples separated by vector expression (Vector positive/Vector negative) using SCANPY
  - <ins>**Project_Tcells_onto_Bulk_EMTAB2319.ipynb**</ins>:
    - Projection of T cell samples onto [Bonnal2015](https://www.nature.com/articles/sdata201551) landscape
  - <ins>**Exhaustion_Sig_calculation.ipynb**</ins>:
    - Calculation of T cell Exhaustion signature