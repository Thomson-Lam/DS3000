



## Lab 1 


1. dot product - transpose; how would that work? (matrix multiplication rules too)
2. scalara transform -- is it a value, or a 1d 1x1 array? 
3. MATRIX VS NUMBER 
4. reshape 

1D array: vector; collection of numbers 

```
np_1d_arr = np.array([1,2,3,4,5])
```

Matrix: surround the vector with []

```
matrix = np.array([[1,2,3,4,5]])
```


.T - transpose 

@ - dot product  ----- **EXPERIMENT!!**

- outcome is a matrix even if there is one element 
- multiplying one dimensional arrays **gives you a number**
- you CANNOT mix 

#### Rules for DP:: 

- dimensionality of matrices (n,n) (m,n) (n,p)
- dot product between matrices = matrix multiplication
- only valid if 1D arrays have the same size


reshape

.item() - brings a number from a collection of data 

- no matrices in DL, but Tensors 

> Note: python treats true as 1 and false as 0; how are booleans represented in dataframes? 

## Columnar dataframes 

SQL -- if needed??? 


Making a new column with variables --- the df becomes a property that you can call functions to operate on it:

```
df['time'] = df.created_at.dt.hour # access daytime property and return the property hour? 
```

> `groupby` 



> TODO: Check code for linear regression and MSE: why was reshaped used?
