# MSBD5001IndividualProject
This repo contains the solution produced by Wong, Tsz Fung for the MSBD5001 Individual Project on kaggle:
https://www.kaggle.com/c/msbd5001-fall2020/overview

Team name: Thomas Wong

Public Leaderboard score: 9.93795 & 10.03450.

Private Leadboard score: 10.64356 (Ranked 7th)

2 submissions were chosen as final.

You can find the submission csv files under ```5001/```.

## Description
The local CV score is around 9.75 MSE.

This CV score is obtained by taking the mean of 100 instances of LightGBM model with CV. (Code not provided)

## Running Locally
The python version I used is Python 3.8.

Install the required packages by running:
```python
pip install -r requirements.txt
```

## Running on Colab (Optional)
The notebook was originally run on Google Colab.

But running on Colab requires you to install the ```holidays``` package by running:
```python
!pip install holidays
```


## How to reproduce the results
Simply run the cells in the jupyter notebook.
It should generate a submission file that scores 10.03450 on the public leaderboard.
The lower score was obtained when the random_state of CV was removed.

