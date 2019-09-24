# India-ML-Hiring

It is a heavily imbalanced binary classification problem, with the ratios of classes being (99.45%:0.55%).

### Type
Binary Classification ( Heaavily Imbalanced )

## Approach
- The dataset provided is heavily imbalanced ( around 99.45%:0.55% for the classes ), hinting towards the possibility of dealing with this problem as a Anomaly detection as well as a classification problem.

- In order to handle the class imbalance, I used the "Scale_pos_weight" parameter present in most of the models and also used Oversampling and Undersampling on the dataset.

- Finally, Undersampling using Tomek Links aced all other oversampling and undersampling methods, so, I have presented that method in the notebook.

- Also, many new features were designed which have been explained along with the logic behind them in the notebook.

- Trained 5 different models trained on 2 types of datasets in order to have a low correlation between the predictions of the model, so that Stacking would be effective.

- The 5 models trained were finally stacked and submitted.

- Thresholding was also used for all the Individual Models as well as the Stacking model so as to give the score a push.


#### Link to the notebook
https://www.kaggle.com/sandeeppat/india-ml-hiring-top-6-kernel
