# Customer Churn Prediction Project

## Project Overview

This project builds a machine learning model that predicts whether a customer is likely to cancel their subscription. The goal is to help businesses identify customers at risk of leaving so that they can take action to improve retention.

---

## Dataset Description

The dataset contains information about customer behaviour and subscription history. It includes features such as:

- Subscription length
- Usage patterns
- Support interactions
- Payment history

The dataset also includes a **target variable** that indicates whether a customer has cancelled their subscription.

---

## Tools Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## How to Run the Project

### 1. Install the required libraries

```bash
pip install -r requirements.txt
```

### 2. Load the dataset

Load the dataset from the `data` folder.

### 3. Train the model

```bash
python churn_model.py
```

### 4. View the experiments and results

Open the Jupyter Notebook:

```text
notebooks/churn_experiment.ipynb
```

---

## Results

The **Logistic Regression** model achieved an accuracy of approximately **82%** on the test dataset.

---

## Future Improvements

Possible improvements include:

- Testing additional machine learning models
- Improving feature engineering
- Tuning model parameters to increase performance

## Decision tree model. 
The model improved its accuracy from 78 per cent to 82 per cent.
