# Predicting Happiness Data Science Project - November 2020
This project attempts to predict the happiness score of a nation based on various international indicators using a variety of modeling techniques. Building a relationship between happiness and the various qualities of a nation could help provide insight on what aspects lead to a generally content population, and this data could be used to improve quality of life. The models can then be used to identify which international indicators are most important to having a happy population. Various models are analyzed throughout the paper, each with its own advantages and disadvantages: linear regression models, K-nearest neighbor classification model, and a non-linear neural network. 

## Datasets
After merging and cleaning data from multiple sources, we had 125 countries with 16 features. The datasets were then  divided into two parts – training dataset comprising of 92 countries and test set with 33 countries. We separated the test set from the training set to remove any sort of bias while predicting the happiness of the countries in the test set. 

## Models
Three types of models were used to predict the happiness scores of countries based on the 16 different international indicators: linear models, classification models, and a non-linear neural network. All models were trained using the same training set, any hyperparameter optimization was performed using a leave-one-out cross validation of that training set, and all models were evaluated with the same test set.  

## References 

[1] “Factors Connected to Happiness.” Psychology, by Rose M. Spielman et al., OpenStax, Rice University, Houston, TX, 2017.  
[2] Ortiz-Ospina, Esteban, and Max Roser. “Happiness and Life Satisfaction.” Our World in Data, 14 May 2013, ourworldindata.org/happiness-and-life-satisfaction.  
[3] Chou, Clementine. “World Happiness Analysis.” Stanford, 3 Nov. 2017, web.stanford.edu/~kjytay/courses/stats32-aut2018/projects/world_happiness_analysis-1.html. 
[4] “Data Analysis of World Happiness Report.” Kaggle, Kaggle, 9 June 2018, www.kaggle.com/koki25ando/data-analysis-of-world-happiness-report.  
[5] Nguyen, XuanKhanh. “Happiness and Life Satisfaction.” Medium, Towards Data Science, 9 Aug. 2020, towardsdatascience.com/happiness-and-life-satisfaction-ecdc7d0ab9a5.  
[6] Bach S, Binder A, Montavon G, Klauschen F, Müller K-R, Samek W (2015) On Pixel-Wise Explanations for Non-Linear Classifier Decisions by Layer-Wise Relevance   Propagation. PLoS ONE 10(7): e0130140. https://doi.org/10.1371/journal.pone.0130140  
