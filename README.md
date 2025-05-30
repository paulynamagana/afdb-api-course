# afdb-api-course
![License](https://img.shields.io/badge/License-MIT-steelblue)

This repository contains Google Colab notebooks developed as part of the **EMBL-EBI course "From sequences to structures: Protein characterisation using EMBL-EBI APIs 2025"**.

---

## About This Repository

This collection of notebooks offers practical, hands-on tutorials for interacting with EMBL-EBI's powerful bioinformatics APIs. The primary focus is on the **AlphaFold Database API**, enabling researchers and students to programmatically access, retrieve, and utilise predicted protein structure data.

## Notebooks Overview

### `1_alphafold-api-introduction.ipynb`

This notebook serves as the foundational introduction to the AlphaFold Database API. It covers:
* **API Request Formulation:** How to construct and send basic API requests to retrieve protein structure prediction data.
* **Response Interpretation:** Understanding the structure and content of the data returned by the API.
* **Programmatic Downloads:** Methods for downloading protein structure files (PDB, CIF) and associated data (such as Predicted Aligned Error (PAE) images and AlphaMissense annotations) directly to your Google Drive.

### `2_afdb_data_visualisation.ipynb`

This notebook focuses on methods to visualize and interpret the data retrieved from the AlphaFold Database, specifically:

* **Parsing pLDDT Scores:** Extracting per-residue confidence metrics from protein structure files.
* **Visualizing pLDDT:** Plotting confidence scores along the protein sequence to identify reliably predicted regions.
* **Analyzing PAE matrices:** Creating visualizations of Predicted Aligned Error to assess the relative confidence of different parts of a protein structure.

### `3_AFDB_BigQuery.ipynb`

This notebook provides a guide to accessing and querying AlphaFold Database information using Google BigQuery. Key topics include:

* **BigQuery Setup:** Instructions on setting up a BigQuery environment to interact with AlphaFold data.
* **Basic Queries:** Constructing SQL queries to retrieve specific protein metadata.
* **Advanced Data Analysis:** Performing complex queries for filtering, aggregating, and analyzing AlphaFold data.


## Course Context

These materials are directly aligned with the learning objectives of the EMBL-EBI course: **"From sequences to structures: Protein characterisation using EMBL-EBI APIs 2025"**.
For more information about the course, please refer to the official [EMBL-EBI Training website](https://www.ebi.ac.uk/training/materials/from-sequences-to-structures-handbook/)

## Getting Started

To begin using these notebooks:
1.  **Open in Colab:** Click the "Open in Colab" badge at the top of this `README.md` (or next to the specific notebook in the "Notebooks Overview" section) to launch the notebook directly in Google Colab.
2.  **Run Cells:** Execute the code cells sequentially. Follow any inline instructions within the notebook for making API calls and interacting with the data.
3.  **Google Account:** Ensure you are logged into your Google account to save your progress, or if the notebook requires mounting Google Drive for file downloads.

