
# Supervised Machine Learning Project
## Finding Donors for CharityML



## Table of Contents  
- [Project Overview](#project-overview)
- [Install](#install)
- [Code](#code)


### <a name="project-overview"></a>Project Overview

This is the project on Supervised Machine Learning Techniques. The goal of this project is to construct a model that accurately predicts whether an individual makes more than $50,000. The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). This project involves with: 
- Data Exploration 
- Data Preprocessing
- Creating a Traininga nd Predicting Pipeline
- Initial Model Evaluation
- Model Tuning
- Extracting Feature Importance 

### <a name="install"></a>Install

The project requires **Python 2.7** and the following Python libraries:

- [NumPy](http://www.numpy.org/)
- [Pandas](pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

[Jupyter Notebook](http://jupyter.org/) is necessary for running the .ipynb files to run the code for the project. 

### <a name="code"></a>Code

All of the code is provided in the Jupyter notebook `finding_donors.ipynb`. 

#### Result
- The optimized model using all features has an accuracy of 0.865 and a F-score of 0.741, which are much higher than Benchmark model's accuracy of 0.248 and F-score of 0.292. 
- Let's refer the data on only the top 5 most important features as the reduced data. The F-score and accuracy score from the final model trained on reduce data are lower than that on full data, but it's not much lower. Accuracy dropped by 0.005 and F-score dropped by 0.013. If training time was a factor, then training on reduced data is beneficial. 