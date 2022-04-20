# RANDOM CLASSIFICATION
## AIM:
To write a python program to perform random classification.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Google Colab /Jupiter Notebook

## Related Theoritical Concept:

## Algorithm
1.
2.
3.
4.

## Program:
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

## Output:
![Ex no 1.Random Classification
![image](https://user-images.githubusercontent.com/86832944/164291264-961e11b3-6a84-4a46-8cab-06e36f9f3f82.png)




## Result:
Thus the random classifier was successfully implemented using python programming.
