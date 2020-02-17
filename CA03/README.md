# Computer Assignment 03 

Applying `Decision Tree Classifier` Algorithm to Census Data

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

```
File Name: CA03_DecisionTree.ipynb
```

### Prerequisites

```
Python 3
CSV Name: census_data.csv
```

### Installing Packages

```
Pandas
Numpy
Matplotlib.pyplot
from IPython.core.interactiveshell import InteractiveShell
from sklearn.tree import DecisionTreeClassifier 
from sklearn.preprocessing import OneHotEncoder
from sklearn.tree import export_graphviz
from sklearn.externals.six import StringIO  
from IPython.display import Image  
import pydotplus
from sklearn.metrics import confusion_matrix, recall_score, precision_score,
                            accuracy_score, f1_score, roc_curve, roc_auc_score, classification_report
from sklearn.model_selection  import RandomizedSearchCV
```

## Running the codes

```
Run through all the codes in Python Notebook
Each code has a comment for clarifying the purpose
```

### Break down into end to end tests

The best model in this project is by setting
`criterion`: "gini"
`min_sample_split`: 4
`min_sample_leaf`: 10
`max_depth`: 7

The scores are
`accuracy`: 0.84
`recall`: 0.59
`precision`: 0.70
`F1-score`: 0.64

## Authors

* **Eric Wu** 

## License

This project is licensed under the LMU MSBA program

## Data Source

The data is from 'https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true'
