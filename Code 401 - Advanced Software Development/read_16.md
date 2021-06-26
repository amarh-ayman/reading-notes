# Machine Learning

- The process of training machines; teaching computers to learn from data and detect patterns. It supports decision making.
- Consists of exploratory analysis(10%), data cleaning (20%), feature engineering(25%), algorithm selection(10%), and model training(15%).

### How to Pick ML Algorithms

Algorithms are chosen based on intuition and practical benefits, rather than math and theory.

> data scientists actually do spend most their time on the earlier steps:

        - Exploring the data.
        - Cleaning the data.
        - Engineering new features.

    Again, that’s because better data beats fancier algorithms.

#### Training the Model

- datasets should be split such that the largest portion is used for training the model, and the remaining smaller portion is used to test the model.
  It is important to mention that models are tested for their ability to predict new, unseen data. Therefore, different data sets should be used for the purpose of testing, as to have reliable models and avoid having overfit models.

###### Hyperparameters

- Tuning "training" the model basically means tuning the hyperparatmeters
- heyperparameters are different from model parameters, in the fact that they cannot be learned directly from the training data.
- **Model parameters:**
  > learned attributes that define individual models.
- **Hyperparameters**
  > express "higher-level" structural settings for algorithms.

###### Cross-Validation

> a method for getting a reliable estimate of model performance using only your training data.

###### Select Winning Model

Selecting the best performing model using testing datasets, according to perfromance metrics: - For regression tasks, we recommend Mean Squared Error (MSE) or Mean Absolute Error (MAE). (Lower values are better) - For classification tasks, we recommend Area Under ROC Curve (AUROC). (Higher values are better)
