# Heart-Disease-ML-Project

## Setup

`pip3 install notebook`
`pip3 install jupyterlab`

## Start Lab

`jupyter lab`

## Heart Disease Datasource

https://archive.ics.uci.edu/dataset/45/heart+disease

### Install the ucimlrepo package

`pip3 install ucimlrepo`

### Import the dataset

```
from ucimlrepo import fetch_ucirepo 
  
# fetch dataset 
heart_disease = fetch_ucirepo(id=45) 
  
# data (as pandas dataframes) 
X = heart_disease.data.features 
y = heart_disease.data.targets 
  
# metadata 
print(heart_disease.metadata) 
  
# variable information 
print(heart_disease.variables) 
```