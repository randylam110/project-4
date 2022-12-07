## **Group 2**

## _Contributors: Randy Lam, Lief Herzfeld, Mai Yang, Thomas Lenzmeier_

____________________________________________________

## Topic : Researching Lung Cancer Attributes

____________________________________________________

# **Overview**
- ### Our group used the *cancer patient data sets.csv* (the link is provided below), to perform a Research Track and as a result show all of the attributes that lead to lung cancer which we would nornamlly not think of. For example, in most cases the leading cause is notably known to be smoking. However, there are a few of other attributes that cause lung cancer according to our the data. 

- ### Our group will present the results of our research analysis in a website, showing some data and visualization to support our findings.


Links: 

- Data: https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link
____________________________________________________

# **Instructions**

## Part 1: Create Repository

 - ### Create a new repository project in GitHub called *lung-cancer-prediction*

 - ### Clone the new repository from GitHub to your computer's desktop then add the notebook files, Resource file, and README file. Remember to commit and push to GitHub regularly.


## Part 2: Preprocessing data in Pandas

 - ### Open a GitBash (Window) or Terminal (Mac) to the *lung-cancer-prediction* repo.

 - ### Change the Python environment to "PythonData38* then launch Jupyter Notebook by typing 'jupyter notebook' and press Enter.

 - ### Use Jupyter notebook to preprocess the *cancer patient data sets.csv* first. To preprocess the dataset, drop columns *index, and Patient Id* since it is not necessary to have these two columns in the sets.  


## Part 3: Using Classification Types in Supervised Machine Learning
 
 1. The K-nearest neighbor (KNN) 
   - #### Use only odd numbers for the k values. From sklearn.neighbors import KNeighborsClassifier. Preprocess the data by dropping the three columns, *index, Patient Id, and Level* and split the data to train and test sets, then fit it to the standardscaler, transform and loop through different k values to find which has the highest accuracy.

 - ### Plot the k values for train and test datasets to figure out where the best combination of scores occurs. this point provides the optimal k value for your model.
 
 2. The Support Vector Machine (SVM)
    - ### From sklearn import svm and fit the data to the model then import classification_report and print the report to show the optimal value. Firstly, preprocess the data by dropping the 3 columns then proceed with the SVM steps.
    - ### Create dataframes for the different levels, *High, Medium, Low* and plot it in a scatter plot graph.
    - ### Split the data to train and test sets and fit the sets to the standardscaler. Import SVM classifier to predict the test set and print the report showing all the average reports.

 3. The Random Forest
   - ### This classification is used to calculate the most important features in *cancer patient data sets.csv*. 
       1. Import SelectFromModel to extract the best features from Random Forests model.
       2. Preprocess the data by dropping the 3 columns first then proceed with the steps for Random Forest.
       3. fit the logistic regression to the original dataset, and then print its score. Compare the two scores of the models.
 
 4. The ROC (Receiver Operating Characteristics) Curves
   - ### This classifier is used by combining the two features of *Low and Medium* into one and label it to 0 to a get a binary classification data in order to compute and plot the ROC Curve (AUC) for the KNN model.

## HTML to GitHub
 1. Host on GitHub: [https://randylam110.github.io/project-4/](https://randylam110.github.io/project-4/)

 2. HTML Files
        a. Home Page (index.html)
        b. Methodology page (methodology.html)
        c. Analysis page (analysis.html)  
        d. Conclusion page (conclusion.html)

 3.  CSS Files (Cascading Style Sheets)
        a. style.css


