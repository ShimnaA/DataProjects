**K Nearest Neighbor**

    Data - [Classified Data]

        classified data set from a company, with hidden feature column names.
        Used KNN to create a model that directly predicts a class for a new data point based on features.

        - Standardized variables, Since Scale of variables matters.
        - Determined Optimal number of clusters (K) using Elbow method
        - KNN model
        - Evaluated model with Classification Report and Confusion matrix

    Data - [KNN_Project_Data csv]

        Repeated the process above on a different Data Set. 

**Decision Tree and Random Forest**

    Data - [kyphosis.csv]

        - Classified using Decision Tree and Random Forest after doing a few data analysis
        - This is a biased dataset as well as small and hence Random Forest did not outperform Decision Tree

    Data - [loan_data.csv]
    
            Public dataset  from LendingClub.com (lending data from 2007-2010)
            Try to classify and predict whether or not the borrower paid back their loan in full. 
    
            - Analysed data using visualization.
            - catergorical feature converted to feature columns with dummy variables.
            - Trained a Decision Tree model and Random Forest model 
            - Evaluated the model
            
**Support Vector Machine**

    Data - [breast Cancer Dataset in Scikit learn]

            - Classified using Support Vector Machine model
            - GridSearchCV to select best C, gamma value
            - Evaluated the model
        