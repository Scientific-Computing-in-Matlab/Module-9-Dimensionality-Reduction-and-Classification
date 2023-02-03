# Module-9 Dimensionality Reduction and Classification

## Objectives
At the end of the module you will be able to 

 - Explain the theory and be able to apply Principal Components Analysis (PCA)
 - Understand the different types of cross-validation 
 - Assess classifier performance using ROC curves/AUC and confusion matrices
 - Apply a Support Vector Machine (SVM) to classify binary data and multi-class data

## Materials
The most efficient way to use the materials in this module are by reading and exploring them in the following order. 

1. Start by reading and going through `./docs/principalComponentsAnalysis.mlx`. 
1. Read and go through an introduction to important concepts in classification in `./docs/classificationIntro.mlx`
1. Learn about the theory and application of Support Vector Machines to binary and multiclass data in `./docs/classificationSVM.mlx'

## Assignments

In this module, we have covered PCA, SVMs, and how to assess them. For this assignment you are being asked to put all of these techniques together. This file Download This file(expressionData.mat) contains a table with the levels of neocortical expression for 67 different genes from 240 mice. The mice are divided into two groups based of off their genotype: Control & Ts65Dn (an animal model of Downs' Syndrome). The purpose of this assignment is to create a script called chainedClassification.m that does the following:

Apply PCA to the data
Take the projections for the first 3 principal components and use them to classify the data according to the mouse genotypes (control or Ts65Dn) using an SVM.
 Plot the projections onto the first 3 PCs, in PC space, and add the support vectors and the separating hyperplane. Make sure that you use different colors to differentiate between the projections of the two classes of mice. 
Cross-validate the SVM using 10-fold cross-validation
Create a figure with 2 subplots: 1 showing the ROC curve , unity line, and the AUC noted somewhere in the figure; 1 showing a confusion chart of the SVM's performance
Write a brief explanation about your observations. Does the SVM perform well overall? Does it classify one class better than another? 
