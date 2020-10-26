# Predicting Viral Host with Metagenomics
# Capstone Project by Jeffrey Jeyachandren
# Machine Learning Engineer Nanodegree


In this notebook, metagenomic features taken from viral genomes are used to predict the the type of host a virus infects. The efficacy of these features are then evaluated. Genome size, GC%, and count of CDS from viral genomes are used as features to predict the viral host (target). SVM techniques are used to create a classifier that achieves 86% accuracy across this dataset. This notebook was created by Jeffrey Jeyachandren (github: JeffinWithYa) as the capstone project for the Udacity Machine Learning Engineer nanodegree. The data for this project came from the 'Genome Information for Sequenced Organisms' Kaggle project: https://www.kaggle.com/superchocolatepain/predict-viral-host-based-on-meta-genomic-features 

**Applies To**
Everyone with the spirit of learning, and anyone interested in computational biology or viral genome data.


## How To Build ##

1. Download the notebook to your computer.
2. Make sure the viruses.csv file is in the same directory.
3. Make sure you are using a python 3.6 kernel environment and have scikit learn installed.


## References ##

1. References can also be found as in-line comments in notebook. 
2. Cleaning up column names: https://stackoverflow.com/a/11346337/6542644 
3. Use of replace method: https://stackoverflow.com/a/20250996/6542644 
4. Counting NaN values in a column: https://datatofish.com/check-nan-pandas-dataframe/
5. Use of plt to plot distributions: https://python-graph-gallery.com/4-add-title-and-axis-label/ 
6. Replace values of 0 with the mean cited from: https://stackoverflow.com/a/11455375/6542644
7. SVM usage adapted from: https://towardsdatascience.com/multiclass-classification-with-support-vector-machines-svm-kernel-trick-kernel-functions-f9d5377d6f02
8. Use of cross_val_score cited from: https://scikit-learn.org/stable/modules/cross_validation.html
9. Data from Kaggle: https://www.kaggle.com/superchocolatepain/predict-viral-host-based-on-meta-genomic-features 


