# melz-documentation
Contains Usage and Examples of all methods of the melz library.

# Getting Started


## Linear Regression
```py
import importlib
lr = importlib.import_module("absotone-melz.LinearRegression")

# X - Features, y = Labels
regressor = lr.LinearRegression(X,y)
```

## Logistic Regression
```py
import importlib
lr = importlib.import_module("absotone-melz.LogisticRegression")

# X - Features, y = Labels
classifier = lr.LogisticRegression(X,y)
```

## Naive Bayes
```py
import importlib
nb = importlib.import_module("NaiveBayes")

# X - Features, y = Labels
classifier = importlib.import_module("absotone-melz.LogisticRegression")
```

