# Principal-Component-Analysis-Custom-Implementation-

## Table of Contents
* [General Info](#general-info)
* [Language](#Language)
* [Requirements](#Requirements)
* [Setup](#setup)
* [Notebook - Compoenents](#Notebook - Compoenents)

## Genral Info
A Jupyer notebook illustrates custom implementation of Principal Component Analysis (PCA) on Breast Cancer Datset available in sklearn

## Language
Python - Jupyter Notebook

## Requirements
* Pandas 
* Sklearn

##  Notebook - Compoenents

```python
#Standardise the data
from sklearn.preprocessing import StandardScaler as ss

scalar = ss()
scalar.fit(data)

data = scalar.transform(data)
```
