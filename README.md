# Bioinformatics Project - Computational Drug Discovery

Welcome to the **Bioinformatics Project** focused on **computational drug discovery**. This project utilizes bioinformatics tools and machine learning techniques to predict bioactivity using data from the ChEMBL database, with a specific focus on the **Butyrylcholinesterase** enzyme.

## Project Overview

This project aims to discover drug candidates by employing machine learning models on bioactivity data. It covers the full workflow from data collection, preprocessing, and descriptor calculation, to predictive modeling and exploratory data analysis.

### Key Objectives:
1. **Data Acquisition**: Retrieve bioactivity data from ChEMBL.
2. **Preprocessing**: Clean and curate bioactivity data.
3. **Descriptor Calculation**: Generate molecular descriptors (Lipinski descriptors, molecular fingerprints).
4. **Model Building**: Train machine learning models (Random Forest, etc.) for bioactivity prediction.
5. **Exploratory Data Analysis**: Perform detailed analysis and visualization of the data.

## Key Features

- **Data Preprocessing**: Handling missing values, removing duplicates, and normalizing IC50 values.
- **Descriptor Calculation**: Use of **RDKit** and **PaDEL** for calculating molecular fingerprints and Lipinski descriptors.
- **Machine Learning Models**: Implementation of **Random Forest** for bioactivity prediction based on molecular descriptors.
- **Feature Importance**: Evaluate feature importance to understand the key factors affecting bioactivity.

## Dependencies & Installation

### Python Libraries:
- **RDKit** for molecular descriptor calculations:
  ```bash
  conda install -c conda-forge rdkit
