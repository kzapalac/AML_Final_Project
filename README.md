# AML_Final_Project
We participate in the Kaggle Competition titled “Child Mind Institute–Problematic Internet Use.” This repository contains all of our code used to explore, proces, and model the data.

File descriptions:

1. DataExploration.ipynb: Notebook that we used to explore all the data. The plots in the EDA section of our blog are from here. The EDA also informed our data processing, so some of that processing is performed here, though it's repeated in our modeling files.
2. AcitgraphyProcessing.ipynb: This files includes some exploration of the actigraphy data as well as the creation of the creation of aggregate activity measures, such as the percentage of time spent sedentary.
3. Advanced_Actigraphy_Processing.ipynb: This file contains our attempt to utilize the actigraphy better through autoencoding.
4. simple_reg_vs_classifier.ipynb: This file contains our first attempt at determining if regression or classification is better.
5. Advanced_Regression_Vs_Classification.ipynb: This file contains our more advanced attempt at determining if we should use regression or classification.
6. best_model.ipynb: This file contains all the methods we tried for pre-processing and our best model (multi-output regression using CATBoost and threshold optimization). The pre-processing settings can be changed at the top of the notebook. We used these settings to explore the best combination of methods that processed the data best.
