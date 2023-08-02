# Thesis

In this project there will be several step to make model for stock trend prediction 

## Preprocess

- At this part, we do exponential smoothing at dataset and calculate label for target model
- After that do create a chart to explore and analyze the data difference

## Feature Extraction

- we build this model to get the insight of feature importance with construction of three decision tree
- We split the dataset with 80% training dataset and 20% testing dataset

## Training and Testing

- Use random search to get the optimal params for each training dataset (each dataset can get different optmial parameters)
- Train model with training set with the optimal parameters for random fores classifier from random search
- Test the model with test set

## Analyze 

- we use different kind of evaluation metrics like ROC_AUC, F1-Score, accuracy, precision, and recall
- Plot the chart to get insight evaluation of model
