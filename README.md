
# Phishing Site Detection

Phishing is a type of cybercrime in which attackers send fake emails or set up fake websites that look legitimate in order to trick people into giving away sensitive information such as login credentials or financial information. Machine learning can be used to detect phishing attacks by training a model on a dataset of known phishing and legitimate websites. In this project, our aim is to use Machine Learning to detect phishing websites. We will be using the data from Kaggle consisting of URLs, half of them are phishing and half of them are legitimate. We will train our data using different algorithms like Decision Tree (DT), Random Forest (RF) and Gradient Boosting, and measure the accuracy of these approaches in predicting the phishing sites.


## Tech Stack

**Tools:** Anaconda, Google Colab, Kaggle

**Programming Language:** Python

##### **Libraries** 
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Sklearn

## Result

Accuracy of various model used for URL detection

||ML Model|	Accuracy|  	f1_score|	Recall|	Precision|
|---|---|---|---|---|---|
0|	Gradient Boosting Classifier|	0.974|	0.977|	0.994|	0.986|
1|	Random Forest|	                0.967|	0.971|	0.993|	0.990|
2|	Decision Tree|      	        0.960|	0.964|	0.991|	0.993|

## Conclusion

1. The final take away form this project is to explore various machine learning models, perform Exploratory Data Analysis on phishing dataset and understanding their features. 
2. Creating this notebook helped me to learn a lot about the features affecting the models to detect whether URL is safe or not, also I came to know how to tuned model and how they affect the model performance.
3. The final conclusion on the Phishing dataset is that the some feature like "HTTTPS", "AnchorURL", "WebsiteTraffic" have more importance to classify URL is phishing URL or not. 
4. Gradient Boosting Classifier currectly classify URL upto 97.4% respective classes and hence reduces the chance of malicious attachments.
