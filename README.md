# Dimensionality reduction and selection of variables

In this challenge we will practice dimensionality reduction with PCA and selection
of variables with RFE.

## Objective

The objective of this challenge is to explore how the PCA works and how we can
get _data sets_ of lower dimensions through it.

For that, we will count on the _data set_ [FIFA 2019] (https://www.kaggle.com/karangadiya/fifa19)
which originally contains 89 variables with different attributes from more than 18 thousand players
of the FIFA 2019 _game_.

## 
Topics

In this challenge we will explore:

* Dimensionality reduction
* PCA
* Selection of variables
* RFE

## Requirements

You will need Python 3 and pip. It is highly recommended to use virtual environments
with virtualenv and the `requirements.txt` file to install the dependency packages
challenge:

```bash
$ pip3 install virtualenv
$ virtualenv venv -p python3
$ source venv/bin/activate
$ pip install -r requirements.txt
```

Windows

```bash
> pip3 install virtualenv
> virtualenv ..\venv -p python3
> ..\venv\Scripts\activate
> pip install -r requirements.txt
```

When finished, you can disable the virtualenv virtual environment with:

```bash
$ deactivate
```
