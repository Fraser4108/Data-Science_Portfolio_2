# Car Sales Prediction Analysis

## Introduction
This repository is a continuation of the car sales analysis (from a previous portfolio) with two new steps:
1. **Train linear regression models** to predict the selling prices of cars.
2. **Evaluate data ethics** from an infographic.

## What is the task?
The analysis is tasked with:
1. **Predictive Modelling**: Building, evaluating, and comparing linear regression models based on feature selection and different training/testing data sizes.
2. **Data Ethics**: Evaluating ethical concerns over a misrepresentation of data.

## What kind of data is used?
The dataset is a cleaned version of `car_sells_clean_data.csv`, which contains the previous columns (year, km_driven, fuel, seller_type, owner, and selling_price). This data is in the formats: float64(1), int64(2), and object(5).

## What algorithms are applied?
- **Linear Regression**: Used to predict selling prices.
- **Feature Selection**: Selecting key features based on their effect on selling price.
- **Training/Testing Split**: Splitting the data into training and testing sets based on the ratio 10% vs. 90% and evaluating how it affects model performance.

## How can you deploy/run the files?
1. Install the required Python libraries.
2. Load the dataset.
3. Run the script.
4. Assess the Ethical Evaluation.

## What are the key takeaways or conclusions?
- **More training data** leads to better predictions.
- **More correlated input features** help generate better results.
- **Small variations in performance** with different settings indicate that the models are not well trained with these input features. Hence, these input features cannot accurately predict selling prices.

### Data Ethics
The ethical principles of accuracy, honesty, fairness, and objectivity have been violated in the case study. This has been done through the misconstruing of the data such that the order of medals reflects national biases.
