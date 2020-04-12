# big-data-assignment
We use two datasets - plants-based, and bank-note authentication datasets for the following analysis methods.  
**Plants-based dataset**: `data.txt` file from https://plants.sc.egov.usda.gov/java/stateDownload?statefips=US04  
**Bank-Note Authentication dataset**: `bill_authentication.csv` from https://archive.ics.uci.edu/ml/datasets/banknote+authentication  
Required files are included this repository.
## Descriptive Analytics
`Big Data Assignment  - descriptive.ipynb`  ; Required file: `data.txt`

Here, the plants-based dataset is analysed and pre-processed with techniques like integer encoding, data imputation, feature selection and data visualisation methods. Processed dataset saved in `plants_data.csv` .

## Predictive Analytics
`Big Data Assignment  - predictive.ipynb`  ;  Required file: `plants_data.csv`

Classification algorithms are used to predict the `Family` attribute of a plant. Techniques used include feature scaling, SVM classifier, DBSCAN clustering, hyperparameter tuning to optimise learning parameters, and itemset mining methods.

## Rules and Patterns
`Big Data Assignment - Rules and Patterns.ipynb`  ;  Required file: `plants_data.csv` 

Using the processed plants dataset, Apriori algorithm is implemented to find frequent itemsets. Further, "interesting-ness" of the rules and petterns generated using various measures is validated.

## Decision Tree and Bayes Classifier
`Big Data Assignment - Decision Tree and Bayes Classifier.ipynb`  ;  Required file: `bill_authentication.csv`  

Decision Tree and Bayes Classifier are used to predict whether a bank note is genuine or forged.




