# SF-Crime-ML-Models
A Statistical Evaluation of Multiclass Machine Learning Models for Crime Classification

This study produces multiclass machine learning models to predict crime categories using Python libraries and a train dataset of 800,000 crime observations in San Francisco between 2003 and 2015. The objective is to identify a model that provides the strongest predictive performance while maintaining robustness and interpretability. 

Three multi-class learner models are evaluated in this project: Categorical Naïve Bayes, Multinomial Logistic Regression, and Random Forest classifiers. Models were developed on the basis of four fundamental functions – a data preparation function, a data preprocessing function, a training function that trains the processed data to a predictive algorithm, and a validation function to evaluate each model using three-fold cross-validation and an independent hold-out test set. Feature engineering included temporal, geographic, and neighborhood variables, with interaction terms incorporated to capture heterogeneous effects across police districts. 

This project presents the methodology in three parts: construction of the four fundamental functions using Python, leveraging the functions to produce and validate the three learner models, visualization of temporal and geographic trends of crime distribution. 
