# A package for R software metrics analysis

## Description
The rsma package provides two things:

- data sets containing software metrics for defect prediction

- functions to run different statistical learning algorithms over the data sets, in order to see which ones perform better for defect prediction

## Datasets
The available data sets come from different repositories. They contain metrics that come from Eclipse software (or its related plugins), NASA, Github or some other source. Most of the metrics are computed from Java or C++ source code. 
To obtain the data sets, install the following packages: 
- rsma.eclipse 
- rsma.github 
- rsma.nasa 
- rsma.quality 

All the data sets available are: 
- eclipse_bug 
- eclipse_change 
- eclipse_churn 
- eclipse_ckoo 
- eclipse_complexity 
- eclipse_entropy 
- eclipse_file 
- eclipse_package 

- github_class_1.0 
- github_class_1.1 
- github_file_1.0 
- github_file_1.1 

- nasa_new1 
- nasa_new2 
- nasa_new3 
- nasa_new4 
- nasa_new5 
- nasa_old1 
- nasa_old2 
- nasa_old3 

- quality_anonymous 
- quality_class 
- quality_method 
- quality_package 

## Statistical and machine learning methods
The functions available perform different algorithms for defect prediction. The methods used are feature selection (to select the best variables), supervised and unsupervised learning (to make the actual prediction models). 
- naive.bayes.results 
- select.backward 
- select.forward 
- select.lasso.conv 
- select.lasso 
- select.logistic 
- select.pca 
- spectral.clustering

## Other functions
Miscellaneous functions to perform different tasks along with the defect prediction algorithms. 
- add.response 
- binary.trans 
- shapiro.wilk.sample 

