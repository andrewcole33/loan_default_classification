# Module 5 Project - Loan Default Classification

## Data Scientist: Andrew Cole

### Goals: 
LendingClub is a peer-to-peer lending company which offers a miscellaneous variety of loan options to anybody seeking one. LendingClub has the applicant enter a variety of background information necessary for loan procedures (credit score, income, term, purpose, FICO ranges, etc.) and then offers that consolidated information to peer investors who can purchase notes of the loans in a non-traditional marketplace. The result is a lower cost to borrow for the borrower, and an easier access to value growth for the investor. The mission is to create a machine learning classification model which can best classify whether a loan recipient, given their application data, will default on the loan or fully pay it off. A variety of classification algorithms will be prepared, tested, and tuned to arrive at the best performing model, which will then be used by LendingClub to measure risk of default.

### Responsibilities:
- Create Github repository for files and efficient tracking of project process
- Research LendingClub's data structure and schemas
- Import necessary libraries for gathering of data 
- Exploratory Data Analysis & preprocessing of gathered LendingClub data
- Split cleaned data into model training & testing sets
- Train multiple classification algorithms with training set
- Tune respective algorithms via adjusting hyperparameters
- Test well performing algorithms on test sets
- Create proper visualizations for explaining processes & outcomes of models
- Create helper modules for efficient running of script
- Create README file for project overview
- Create presentation slide deck 
- Present concepts & actionable insights

### Summary of Included Files:
- Mod_5_project_main.ipynb
    - Jupyter Notebook for technical audience
    - PEP 8 Standards
    - Imports necessary packages for EDA & model testing
    - Library importation, statistical testing, hyperparameter tunings 
    - Models tested: Random Forrest, Random Forest w/ GridSearch, KNN, XGboost, SVM, Logistic Regression
    
- README.md
    - See whole file
    - Overview of project including goals, responsibilities, & summary of included files
    
- LendingClub_Loan_Classification_Presentation
    - Google slides deck for presentation
    - Includes non-technical summary of goals & procedures
    - Actionable Insights for LendingClub
    
- LCloans_07.csv
    - CSV file containing LendingClub loan data
    - Years: 2007-2011
    - 42000 entries 
    
- LCDataDictionary.csv
    - CSV file
    - Contains feature definitions for LCloans_07.csv file