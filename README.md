# Single-cell RNA-seq and Spatial Transcriptomics Training

This repository contains educational materials for learning **single-cell RNA-seq** and **spatial transcriptomics** analysis.

The course is designed as a simple learning path:
first, study the lecture slides, then run the related Google Colab notebooks.

All notebooks are prepared to run in **Google Colab**.
The required datasets are downloaded directly inside the notebooks, so there is no need to manually download or store large data files in this repository.

---

## Course Overview

This training covers the basic concepts and practical analysis steps for:

* Single-cell RNA-seq data
* Count matrix, cell barcode, and UMI
* Quality control
* Normalization
* Highly variable genes
* PCA and UMAP
* Clustering
* Cell type annotation
* Differential expression analysis
* Spatial transcriptomics
* Visium/spatial data structure
* Spatial visualization
* Spatial neighborhood analysis
* Spatially variable genes

---

## Repository Structure

```text
.
├── README.md
├── slides/
│   ├── session-01-single-cell-introduction.pdf
│   ├── session-02-single-cell-analysis.pdf
│   ├── session-03-spatial-transcriptomics-introduction.pdf
│   └── session-04-spatial-analysis.pdf
│
├── colab/
│   ├── 01-scrna-seq-analysis.ipynb
│   ├── 02-Spatial-transcriptomics.ipynb
│   
│   
│
└── assignment/
    ├── Assignment_2.pdf
    ├── Assignment_3.pdf
    
    
```

---

## How to Use This Repository

The recommended order is:

1. Open and read the lecture slides from the `slides/` folder.
2. Open the related Colab notebook from the `colab/` folder.
3. Run the notebook step by step in Google Colab.
4. Complete the Assignment related to each session.

---



## Running the Notebooks in Google Colab

All notebooks are designed to run online using Google Colab.

To run a notebook:

1. Open the notebook file from the `colab/` folder.
2. Click **Open in Colab** if the badge/link is available.
3. Run the cells from top to bottom.
4. The required packages and datasets will be downloaded inside the notebook.

You do not need to install Python, Scanpy, Squidpy, or other packages on your personal computer.

---

## Data

The datasets are **not stored in this repository**.

Each Colab notebook contains the required commands for downloading or loading the data online.

This keeps the repository lightweight and avoids uploading large biological data files directly to GitHub.

---

## Requirements

No local installation is required.

The notebooks are intended to be executed in:

* Google Colab
* Python runtime inside Colab
* Online data download inside each notebook

Some notebooks may install required packages such as:

```python
scanpy
squidpy
anndata
numpy
pandas
matplotlib
```

These installation commands are already included inside the notebooks.

---

## Suggested Learning Path

For best results, follow this order:

### Step 1 — Read the slides

Start with the PDF slides to understand the biological and computational concepts.

### Step 2 — Run the Colab notebook

After studying the slides, open the related Colab notebook and run the code step by step.

### Step 3 — Check the outputs

Look carefully at the generated plots, tables, clusters, and spatial visualizations.

### Step 4 — Complete the exercises

Use the exercises to review the main ideas and practice interpretation of the results.

---

## Notes

* This repository is prepared for educational purposes.
* The notebooks are simplified for teaching and learning.
* Some package installation steps may take a few minutes in Google Colab.
* If a notebook runtime is disconnected, restart the runtime and run the notebook again from the beginning.
* The analysis results may slightly change depending on package versions and Colab runtime updates.

---

License

This repository is provided for educational and academic use.

You may use, share, and adapt these materials for teaching, learning, and non-commercial academic purposes, provided that proper credit is given to the author and this repository.

Commercial use, redistribution as a paid course, or use of these materials without attribution is not permitted without prior permission.

The code and Colab notebooks are provided as educational examples and may require modification depending on the runtime environment and package versions.

Author

Prepared for educational training in single-cell RNA-seq and spatial transcriptomics.

If you use these materials in teaching, training, or research, please cite or reference this repository.
