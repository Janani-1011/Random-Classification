### EX NO: 01
### DATE: 04/04/2022
# <p align= "center">RANDOM CLASSIFICATION</p>
## AIM:
To write a python program to perform random classification.

## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Google Colab /Jupiter Notebook

## RELATED THEORETICAL CONCEPTS:
Random classifier: It creates a set of decision trees from randomly selected subset of training set. It then aggregates the votes from different decision trees to decide the final class of the test object. Random Forest is suitable for situations when we have a large dataset, and interpretability is not a major concern.

Purpose of Random classifier: One of the most important features of the Random Forest Algorithm is that it can handle the data set containing continuous variables as in the case of regression and categorical variables as in the case of classification.

## ALGORITHM:
1.  In Random forest n number of random records are taken from the data set having k number of records.
2.  Individual decision trees are constructed for each sample.
3.  Each decision tree will generate an output.
4.  Final output is considered based on Majority Voting or Averaging for Classification and regression respectively.

<br>
<br>
<br>
<br>
<br>
<br>
<br>


## PROGRAM:
```
/*
Program to implement random classification.
Developed by   : JANANI D
RegisterNumber :  212220040056
*/


import matplotlib.pyplot as plt
from sklearn import datasets
x,y=datasets.make_blobs(n_samples=100,n_features=2,centers=2,cluster_std=1.05,random_state=2)
fig=plt.figure(figsize=(10,8))
plt.plot(x[:,0][y==0],x[:,1][y==0],'r^')
plt.plot(x[:,0][y==1],x[:,1][y==1],'bs')
plt.xlabel("feature 1")
plt.ylabel("feature 2")
plt.title('Random Classification Data with 2 classes')
```
<br>

### OUTPUT:

![Screenshot (109)](https://user-images.githubusercontent.com/86832944/170853449-b915f697-4b54-4f13-acb6-6f7a51a81ae7.png)



## RESULT:
Thus the random classifier was successfully implemented using python programming.
