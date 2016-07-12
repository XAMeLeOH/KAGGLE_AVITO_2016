# KAGGLE_AVITO_2016
Avito Duplicate Ads Detection

## HowTo run

All data files should be contained in the **data** directory.

Script used joblib's [Memory](https://pythonhosted.org/joblib/memory.html) feature to cache intermediate results. So it assumes there is also **avito-cache** folder in the current directory.

`$ jupyter-nbconvert --to=python avito_xgb.ipynb`

`$ nice -n 19 python avito_xgb.py test`
