# Learn how to use ramdon forest
 
 
### n_ Estimators (number of trees)
* It represents the number of trees established.
* Generally speaking, the more trees there are, the better the performance and the more stable the prediction will be, but this will also slow down the calculation speed.
* Generally speaking, it is a better choice to choose hundreds of trees in practice. Therefore, the general default is 100.

### n_ Jobs (number of processors allowed by the engine)
* The super parameter indicates the number of processors the engine allows to use.
* If the value is 1, only one processor can be used.
* A value of -1 means there is no limit.
* Set n_ Jobs can speed up the calculation of the model.

● gini: measures Gini index 

● entropy: measures information gain 


