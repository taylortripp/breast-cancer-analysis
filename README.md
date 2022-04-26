# breast-cancer-tumour-prediction

This repository demonstrates implementation of various machine learning models to predict whether a breast cancer tumour is benign or malignant. The predictive modelling can be found in the Jupyter Notebook.

Four different models were used and, subsequently, compared with one another to determine that which had the highest accuracy in labelling a tumour as either benign or malignant. These four models are:
* Logistic Regression (LR)
* Random Forest (RF)
* k-Nearest Neighbours (kNN)
* Support-Vector Machine (SVM)

While the accuracy scores of each model turned out to be relatively high (all above 85%), it is worth noting that the dataset used was not only small (less than 600 records) but that it was also imbalanced (about two-thirds of the tumours were benign). This has implications for reliability and generalization of these results onto a larger population.

Additionally, there is a *Tableau* dashboard ([Breast Cancer Dashboard](https://public.tableau.com/views/Breast_Cancer_Dashboard/BreastCancerDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)) that accompanies the Jupyter Notebook. This infographic dashboard displays the state of breast cancer in Canada (as of 2021), including such metrics as case counts by province, survival statistics, and ways in which risk of developing breast cancer can be reduced. Though the data in this dashboard pertain to individuals of all genders, it is worth noting that the vast majority of breast cancer cases—and available statistics, more broadly—are among females.
