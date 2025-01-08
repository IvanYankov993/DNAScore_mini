# DNAScore_mini

**DNAScore_mini** is a lightweight version of the DNAScore project, presenting a machine learning (ML) model specifically for DNA melting temperature (Tm) determination. This repository focuses on **chemically modified dsDNA**.

## Key Features

### Model 1 - Chemically Modified dsDNA
This model determines the melting temperature (Tm) of chemically modified DNA duplexes.

### ML Model Components:
- **PDB File Processing**: A class for processing PDB files and extracting features related to DNA stability (DNAScore features).
- **Random Forest (RF) Model**: A class for the RF model, including hyperparameter optimization for optimal performance.
- **Trained Models**: The trained version of Model 1 is available in pickle format for easy use in applications.

## Usage Instructions

### How to Use the RF Model
Instructions are provided on how to use the trained RF models to predict Tm.

### Structure Generation Protocol
A recommended structure generation protocol for preparing input data before model prediction is included.

### k-Fold Cross Validation
Figures and results from k-fold cross-validation experiments on Tm prediction accuracy are included for reference.

## Limitations
**DNAScore_mini** does not include:
- Code for model-feature combination investigations.
- Predictions of thermodynamic properties such as ΔG (Gibbs free energy), ΔS (entropy), or ΔH (enthalpy).
- Alternative models such as Multiple Linear Regression (MLR), k-Nearest Neighbors (KNN), RF, STCNN, or MTCNN.
- Alternative features like string features (OHEP, OLE), sequence statistics, or other versions of DNAScore (e.g., RDScoer).
- The impact of structure generation protocols using models like AF3, or template generation using tools such as AmberTools, NAB, or w3DNA.
- Workings with natural, mismatched, or chemically modified DNA duplexes outside of Model 1.

## Additional Notes
For more comprehensive research and access to the full **DNAScore** project, please reach out to [ivan.yankov.2016@uni.strath.ac.uk](mailto:ivan.yankov.2016@uni.strath.ac.uk).
