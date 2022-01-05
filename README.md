# Predict Bike Sharing Demand

## Overview

Create a Kaggle account if they do not already have one, download the Bike Sharing Demand dataset, and train a model using AutoGluon. They will then submit their initial results for a ranking.

After the first workflow iterate on the process by trying to improve their score. This will be accomplished by adding more features to the dataset and tuning some of the hyperparameters available with AutoGluon.

Finally, submit all their work and write a report detailing which methods provided the best score improvement and why.

To meet specifications, the project will require at least these files:
* Jupyter notebook with code run to completion
* HTML export of the jupyter notebbook
* Markdown or PDF file of the report

## Getting Started
* Proceed with the project within the [jupyter notebook](project-template.ipynb).
* Visit the [Kaggle Bike Sharing Demand Competition](https://www.kaggle.com/c/bike-sharing-demand) page. There you will see the overall details about the competition including overview, data, code, discussion, leaderboard, and rules. You will primarily be focused on the data and ranking sections.

### Dependencies

```
Python 3.7
MXNet 1.8
Pandas >= 1.2.4
AutoGluon 0.2.0 
```

### Installation
```
pip install jupyterlab
```
## Project Instructions

1. Create an account with Kaggle.
2. Download the Kaggle dataset using the kaggle python library.
3. Train a model using AutoGluon’s Tabular Prediction and submit predictions to Kaggle for ranking.
4. Use Pandas to do some exploratory analysis and create a new feature, saving new versions of the train and test dataset.
5. Rerun the model and submit the new predictions for ranking.
6. Tune at least 3 different hyperparameters from AutoGluon and resubmit predictions to rank higher on Kaggle.
7. Write up a report on how improvements (or not) were made by either creating additional features or tuning hyperparameters, and why you think one or the other is the best approach to invest more time in.
