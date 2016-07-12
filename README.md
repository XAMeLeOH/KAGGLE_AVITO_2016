# KAGGLE_AVITO_2016
Avito Duplicate Ads Detection

## HowTo run

All data files should be contained in the **data** directory.

Script used joblib's [Memory](https://pythonhosted.org/joblib/memory.html) feature to cache intermediate results.

`$ jupyter-nbconvert --to=python avito_xgb.ipynb`

`$ nice -n 19 python avito_xgb.py test`
