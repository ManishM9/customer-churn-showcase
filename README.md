# Customer churn prediction: academic case study

A university project exploring whether tabular credit card customer data can help identify likely churn. This repository is a **public case study only**. The academic implementation, trained artifacts, and evaluation outputs are not published here, so the results cannot be independently reproduced from this repository.

## Problem and data

The project addressed customer attrition in a credit card portfolio as part of the University at Buffalo's CSE 587 Data Intensive Computing course. The earlier project notes identify [BankChurners.csv](https://github.com/susanli2016/Machine-Learning-with-Python/blob/master/data/BankChurners.csv) as the dataset. The intended target was customer attrition; this README does not assert a particular train/test split, class balance, or business impact because supporting artifacts are unavailable here.

## Reported approach

Earlier project notes describe exploratory analysis, duplicate and outlier handling, missing-value imputation, categorical encoding, and normalization. They list k-nearest neighbors, naive Bayes, logistic regression, support vector machines, decision trees, and random forests as models considered. The notes also describe an Angular form, a Node.js API, and a Python prediction process for a local demonstration.

A sound comparison would fit preprocessing on training data only, use a held-out set or cross-validation, compare against a baseline, and report the confusion matrix, precision, recall, F1, and class-specific performance. The artifacts needed to verify whether each step was followed are not included here.

## Results and limitations

An older README listed model accuracy values, including 95.5% for random forest. Those figures have been removed from the public summary because the split, class distribution, evaluation outputs, and code are unavailable for verification. No deployed model or production validation is claimed. Accuracy alone can obscure performance on the churn class. The local demo and any predictions should be treated as academic work.

## Demonstration

The earlier README included this [project screenshot](https://github.com/user-attachments/assets/e647b832-e0cf-4de1-9ed5-b20f0f6f2747). It is a visual reference, not evidence of model quality.

## Contribution and access

Manish Malepati contributed to this course project. Individual code ownership cannot be verified from this documentation-only repository. The academic source remains private; access is subject to course rules. Contact [Manish Malepati](mailto:manish.malepati@gmail.com) for questions about the work.
