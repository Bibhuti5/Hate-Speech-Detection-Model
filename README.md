 # Hate Speech Detection Model
The data set I will use for the hate speech detection model consists of a test and train set. The training package includes a list of 31,962 tweets, a corresponding ID and a tag 0 or 1 for each tweet. The particular sentiment we need to detect in this dataset is whether or not the tweet is based on hate speech. You can download the dataset from here.

# Data Cleaning
Data cleaning is the process of preparing incorrectly formated data for analysis by deleting or modifying the incorrectly formatted data which is generally not necessary or useful for data analysis, as it can hinder the process or provide inaccurate results. Now I will perform the process of data cleaning by using the re library in Python.

# Handling Imbalanced data for Hate Speech Detection Model
If you will deeply analyse the task we are working on with context to the data we are using, you will find that the tweets regarding hate speeches are comparatively lesser than others, so this is a situation of an unbalanced data.

If we will fit this data to train our hate speech detection model, then the model will not generalize any hate speech because the data with context to the hate speech is very less than the positive ones. So in this situation, we need to prepare the data to fit properly in our model.

There are a number of methods you can use to deal with this. One approach is to use either oversampling or downsampling. In the case of oversampling, we use a function that repeatedly samples, with replacement, from the minority class until the class is the same size as the majority.

# Creating a Pipeline
For simplicity and reproducibility of the hate speech detection model, I will use the Scikit-Learn’s pipeline with an SGDClassifier, before training our model.

# Bibhuti Bhusan sahoo

### Portfolio:- https://bibhutiport.blogspot.com/

### Github:-    https://github.com/Bibhuti5

### Linked In:- https://www.linkedin.com/in/bibhutibhusansahoo97/
