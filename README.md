Final project for DS4021!! :) 

need to do: 
- add notebooks for ensemble
- update the tree below for new files

# DS4021 Final Project Repository

This repository contains all the code, data, and documentation for the DS4021 final project. Our project focuses on analyzing survey data to determine if an individual's self reported anxiety (1-10) can be predicted from their music preferences.

**Team Members:** Amelia Vasiliu, Jessica Ni, Ruth Melese

## Section 1: Software and platform section
This project uses the following tools and environments:
- Python: 3.x
- Environment: Jupyter notebooks
- Packages
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - PyTorch
- Operating System: Windows/Linux/MacOS

## Section 2: Project Structure
The project is organized into the following directories and files:

```
ML4021-final-project/
├── Data/
│   ├── mxmh_survey_results.csv                # Original dataset
│   ├── X_test.csv                             # Test features
│   ├── X_train.csv                            # Training features
│   ├── y_test.csv                             # Test labels
│   └── y_train.csv                            # Training labels
├── NOTEBOOKS/
│   ├── Descriptive_Analysis.ipynb             # Notebook for descriptive statistics and visualizations
│   ├── EnsembleModels.ipynb                   # Notebook for ensemble models
│   ├── Final_Test.ipynb                       # Final Test Notebook
│   ├── NeuralNetwork.ipynb                    # Notebook for neural network model implementation
│   ├── SVM.ipynb                              # Notebook for SVM model implementation
│   └── Penalized_Linear_Model.ipynb           # Notebook for Penalized Linear Model implementation
├── OUTPUT/  
│   ├── DA_age_kdeplot.png                      # Descriptive analysis plots
│   ├── DA_hoursperday_agegroup_boxplot.png
│   ├── DA_hoursperday_barplot.png
│   ├── DA_hoursperday_whileworking_boxplot.png
│   ├── DA_streamingservices_barplot.png
│   ├── DA_top10genres_barplot.png
│   ├── Coeff_Comparison.png                    # Linear model plots
│   ├── Lasso_MSE_vs_alpha.png
│   ├── NeuralNetwork_traininglosscurve.png
│   ├── Ridge_MSE_vs_alpha.png
│   ├── Ridge_Pred_v_Actual_TEST.png
│   ├── Ridge_Residuals_TEST.png
│   ├── SVR_Pred_v_Actual.png
│   ├── SVR_Residuals.png
│   ├── NeuralNetwork_actualvspredicted.png     # Neural network model plots
│   ├── NeuralNetwork_gridsearchresults.png
│   ├── NeuralNetwork_residualshistogram.png
│   └── NeuralNetwork_traininglosscurve.png
├── README.md
```
