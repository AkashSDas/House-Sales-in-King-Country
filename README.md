

# House Sales in King Country, USA

  

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

  
  

## Table of contents

  

*  [About](#about)

* [Technologies Used](#technologies-used)

* [Results of the Project](#results-of-the-project)

*  [Installation](#installation)

*  [Data Source](#data-source)

*  [License](#license)

  
  

## About

>In this project using the dataset of **`House Sales in King Country, USA`** from `Kaggle` to build a system that predicts the price of a House in King Country, USA.

> In this project doing `feature engineering`on `numerical` and `categorical`data and selecting the features that affects the price of the house.

> After `scaling` and `splitting` the data into training and testing dataset `cross validation` is performed and the `parameter tuning` is done. At last the model is tested on the test data and is `evaluated` on the basis of `mean squared error` and `r2 score`.

## Technologies Used

> [![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/) is used as Programming Language.

>  `Numpy` is used for the mathematical and data manipulation.

>  `Pandas` is used to analysis and manipulation of data.

> `Matplotlib` and `Seaborn` are used for data visualisation which helped in the analysis of data.

> `SciPy` is used to perform statistical operations which is used to deal with outliers.

> `Sciki-learn` is used for data preprocessing, creating machine learning model and evaluating it, thus creating a pipeline.

> `Pipenv` is the virtual environment used for the project. `Jupyter Notebook` is used to for the entire data science and machine learning life cycle.  

## Results of the Project

####  Metrics Scores

![Metrics Scores](https://github.com/AkashSDas/House-Sales-in-King-Country/blob/master/project-results-images/metrics-scores.png)

#### Actual VS Prediction

![Actual VS Prediction](https://github.com/AkashSDas/House-Sales-in-King-Country/blob/master/project-results-images/actual-vs-prediction.png)

## Installation

  

It is highly **recommended** to use **`virtual enviroment`** for this project to avoid any issues related to dependencies.

  

Here **`pipenv`** is used for this project.

  

There is a **`requirements.txt`** file in `'House-Sales-in-King-Country'/requirements.txt` which has all the dependencies for this project.

  

- First, start by closing the repository

  

```bash
git clone https://github.com/AkashSDas/House-Sales-in-King-Country
```

  

- Start by installing **`pipenv`** if you don't have it

```bash
pip install pipenv
```

  

- Once installed, access the venv folder inside the project folder

```bash
cd  'House-Sales-in-King-Country'/venv/
```

  

- Create the virtual environment

```bash
pipenv install
```

The **Pipfile** of the project must be for creating replicating project's virtual enviroment.

  

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

  

- Enable the virtual environment

```bash
pipenv shell
```

  

- dataset, jupyter notebook and model are in `'House-Sales-in-King-Country'/venv/src` folder.

  

```bash
cd src/
```

  

- To start/view the jupyter notebook

```bash
jupyter noterbook
```

  

This will open a webpage in the browser from there you can click on notebook.ipynb to view it.
  

## Data Source

> This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.

This dataset can be found in Kaggle - <a href='https://www.kaggle.com/harlfoxem/housesalesprediction'>Source</a>

## License

  

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
