# Breast Cancer Prognosis Using Supervised Machine Learning

## EECS 349 Northwestern University, Fall 2018

### Team Members
Alexander Alwan and David MacCumber

### Contact Us
alexanderalwan2019@u.northwestern.edu

davidmaccumber2021@u.northwestern.edu

<img src="https://www.sacofitness.com/wp-content/uploads/2017/10/banner.png" width=20%> 

## Introduction
Breast cancer is the second most common cancer worldwide, and it is the second leading cause of women’s death from cancer. Improving cancer prognosis has been a problem of primary concern towards improving clinical management and treatment decision making for cancer patients. Additionally, the number and size of medical databases are increasing rapidly and most of these data have yet to been probed for valuable and unseen information. As these databases become more complex and rich with patient information, medical practitioners face greater difficulty in making accurate diagnoses and prognoses. 

Our task is to develop predictive models for cancer prognosis. Specifically, we wish to predict the likelihood that a breast cancer patient’s tumor is benign or malignant under various supervised machine learning algorithms in the Waikato Environment for Knowledge Analysis (Weka). As such, we will make use of a datatset from an existing data repository geared towards machine learning tasks. It was obtained from the University of Wisconsin Hospitals, Madison from Dr. William H. Wolberg. The data was collected over a two year period from 1989-1991 and contains 699 instances (examples) with 10 attributes and two classifications (maligant and benign cancerous cells). 

## Machine Learning Tasks 
We implemented various machine learning tasks for this project. Specifically, we utilized the ZeroR algorithm, logistic regression, naive bayes classifiers, decision trees (with and without pruning), k-nearest neighbors, and multilayer perceptrons. Additionally, for each of these classification techniques, we implemented 10-fold cross validation to assess the model's accuracies.  

Our solutions performed quite well on this dataset, as each of our models had at least a 92% classification accuracy (with the exception of the ZeroR algorithm which we used as a benchmark to assess all of our other models). Each model's performance (in the form of model accuracies) can be viewed in the bar graph below. The model that achieved the highest CV accuracy was logistic regression with an accuracy of 96.57%.  

![Model Accuracies](/images/model_accuracies.png)


The link to our final report can be found here: [Final Report](https://docs.google.com/document/d/1hB5TiP_qrpGs4ZGKCB7zV3M-geFUmaiaO93cZD5dvwE/edit?usp=sharing%5C)





