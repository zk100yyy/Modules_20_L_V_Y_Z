# Modules_20_L_V_Y_Z
### Our Selected Topic: The Titanic
### Why we picked this Topic: Because this topic's initial data is relatively more accessible,the event itself has been a public focus ever since the “unsinkable” RMS Titanic sank after colliding with an iceberg in 1912. 
### The source of data: We will use two data sets for this project,one dataset is titled `train.csv` and the other is titled `test.csv`.
### Questions hope to answer with the data: With the passengers being in different ages and socioeconomic status, many people fortunately survived and many died,We want to build a predictive model that answers the question: “what sorts of people were more likely to survive?"


## Second Week 

Goal for this Final Project:
My team will show a simple example of an analysis of the Titanic disaster in Python using a full complement of PyData utilities. 
This is aimed for those looking to get into the field or those who are already in the field and looking to see an example of an analysis done with Python.

This Notebook will show basic examples of:
* Data Handling
* Importing Data with Pandas
* Cleaning Data
* Exploring Data through Visualizations with Matplotlib
* Merage two CSV files into one DataBase

•	Description of preliminary data preprocessing
The Titanic shipwreck was a massive disaster, so we will implement data pre- processing on this data set to know the number of survivors and their details. 
First, we start off by importing all the data into our system, training data set and testing data set are given by Kaggle and we will download from Kaggle. 

In our case we chose to load data with pandas,next, we have Meraged the two CSV files( Train.cvs file and test.vcs file) into one DataBasewe.
And we will be dropping columns that don’t contribute much to our model such as “name, ticket, cabin etc.”. 
If needed, we can drop the rows with missing values (NaN). We then convert “Pclass, Sex, Embarked values” into columns, dropping the same 
columns from the data frame. To handle the missing value, age, we compute a median of all the ages. Jumping into splitting the data set into training set and test set. 
The dataset is split 70% training and 30% test. 

•	Description of preliminary feature engineering and preliminary feature selection, including the decision-making process
Feature preliminary engineering includes titles, deck, family size, age* classification, and fare per person. 

•	Description of how data was split into training and testing sets
 For the training set was based on “features” like passengers’ gender and class., we provide the outcome for each passenger. 
 For the test set, we do not provide the ground truth for each passenger. We predict these outcomes. For each passenger in the test set, use used the model to predict
 whether they survived the sinking of the Titanic.
  
•	Explanation of model choice, including limitations and benefits
