# Airbnb-Superhost-Predictor
A logistic regression model to predict Airbnb superhosts with Skikit-learn

## Usage
Load the scikit-learn model stored in the pickle file.
``` python
import pickle
from sklearn.linear_model import LogisticRegression

model = pickle.load(open('Airbnb_superhost_classification_model.pkl', 'rb'))
```
