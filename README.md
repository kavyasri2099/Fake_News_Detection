# Fake_News_Detection  

Project Overview:  
This project involves building a classifier to detect fake news using natural language processing (NLP) and machine learning techniques. The dataset used contains text labeled as fake or real news, and various machine learning models are trained and evaluated to determine their effectiveness in classifying the news articles.  

Dataset:  
The dataset contains news articles with the following attributes:  

- text: The content of the news article.  
- label: The label indicating whether the news is fake (0) or real (1).
  
Requirements:  
The following Python libraries are required to run the code:  

- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- wordcloud

Data Preprocessing:  
Loading the Data: The dataset is loaded using pandas.    
Handling Duplicates: Duplicate entries are removed from the dataset.

Exploratory Data Analysis (EDA):  
Distribution of fake vs. real news.  
Distribution of text length in the articles.  
Word clouds for fake and real news articles.  

Machine Learning Models:  
Train-Test Split: The dataset is split into training and testing sets.  
Text Vectorization: Using TfidfVectorizer to convert text data into numerical format.  

Model Training and Evaluation:  
- Naive Bayes  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest  
- Gradient Boosting  

Files:
fakenews.csv: The dataset containing news articles.
fakenews_classifier.ipynb: Jupyter Notebook containing the code for data preprocessing, EDA, and model training.
fakenews_eda_presentation.pptx: PowerPoint presentation summarizing the project.

Conclusion:
This project demonstrates the process of building a fake news classifier using various machine learning models. The models are evaluated based on their performance metrics, and the results are visualized to provide insights into the effectiveness of each model.

