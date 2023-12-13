# K-means clustering model for California housing data

The aim of this project is to classify the median household income of California's US census areas (i.e., blocks) into 6 groups based on the proximity of the blocks. To perform the classification of the 6 groups, a K-means clustering estimation will be performed. Following this estimation, random forest estimation will be conducted using the 6 groups as dependent variable.

## Folder content:

*  Data folder: contains the datasets used in this project
    * Processed folder: contains the final train and test datasets used in the machine learning models

*  Models folder: contains the final models used in this project (e.g., the k-means and the random forest)

*  scr folder: contains all the notebooks with the code of this project 
    * The notebook **'Expl_Data_Analysis.ipynb'** contains all the exploratory data analysis with the full dataset and then splits the data intro training and test. For simplification and purpose of this project, the models will only be trained with 3 variables (median household income, latitude, and longitude)   

    * The notebook **'Model_estimations.ipynb'** contains all the estimations of the unsupervised and supervised