# FNOPI Classification
This repository contains the code and resources for the FNOPI (Federazione Nazionale degli Ordini delle Professioni Infermieristiche) Classification project, developed by the Methodology team at ISTAT. The goal of this project is to classify and categorize nursing-related documents using NLP models, clustering and semantic search.

## Project Description
The FNOPI Classification project provides tools and scripts to:

- Preprocess text data related to nursing and healthcare professions.

- Apply models to assign codes to documents and to create clsuters from documents.

This work is part of the broader ISTAT efforts to support statistical analysis in the healthcare sector, improving the understanding of nursing professions and their distribution across Italy.

## Repository Structure
Here’s an overview of the repository’s main components:

### 📁 classifications
Contains classification files, such as `NIC_classification.csv`, that map nursing interventions or services to NIC categories.

### 📁 csv
Includes CSV files with cleaned and preprocessed data, such as:

- N_prestazioni_by_note_infermieristiche.csv – number of nursing interventions by notes
- N_prestazioni_by_macroprestazione.csv - number of nursing interventions by text of macro catoegory of intervention
- N_prestazioni_by_cod_valoremedio_liquidazione.csv - number of nursing interventions by code of average value of settlement
- other intermediate data used for classification tasks

## Installation
Clone the repository:

```bash
git clone https://github.com/istat-methodology/fnopi-classification.git
cd fnopi-classification
```

Install dependencies (if any):

```bash
pip install -r requirements.txt
```

Example notebooks and scripts demonstrate the workflow for data preprocessing, model training, and evaluation.

## License
This project is licensed under the MIT License (or specify another license, if applicable).

## Contact
For questions or feedback, please contact the ISTAT Methodology team.
