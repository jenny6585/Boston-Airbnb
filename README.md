# Boston-Airbnb
> This is a project from the Udacity Data science course.

### Content

> 1. Introduction, Objective
> 2. Datasets
> 3. Install
> 4. Libraries
> 5.Analysis
>> 1. Business Understanding
>> 2. Data Understanding(EDA)
>>3. Data Preparation
>> 4. Model
>> 5. Results
> 6. Conclusion

### 1. Introduction, Objective

This is my first project for Udacity program. It uses the data about Boston's rental housing Airbnb has provided. This project focuses on the following 4 questions.

> 1. Distribution of Price, and supply and demand
> 2. Correlations between Price and other Features
> 3. Price pridiction model using Linear Regression Algorithm
> 4. The most frequently used comments in the Review dataset

### 2.Datasets
This project uses 3 datasets about the Airbnb accomomdations in Boston.
<blockquote> calendar.csv</blockquote>
<blockquote>listings.csv</blockquote>
<blockquote> reviews.csv</blockquote>

### 3.Install
```
pip install nltk
```
```
import nltk
nltk.download('english')
```

### 4.Libraires
```
import pandas as pd
import numpy as np
from scipy import stats

%matplotlib inline
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score, mean_squared_error

from nltk.corpus import stopwords  
from nltk.tokenize import word_tokenize 
```
### 5. Analysis

### 6. Conclusion
- After finding out the most frequently used comment word, I could find out most of the words positive, such as great, clean, nice, comfortable. From this fact I could guess that clients who were satisfied mostly left a review. 

- From the calendar dataset I found out that demand out numbered the supply most of the month. So the company could try to increase the supply in the Boston region.

- The rate for one night was mostly focused between $150~160. And the type, beds, bedrooms, bathroom, review of cleanliness and location were the features related to the price.


### 7. Blog post
https://medium.com/@jjenny6585/boston-airbnb-analysis-1bb56fb642a6
