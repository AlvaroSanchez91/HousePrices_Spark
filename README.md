# House Prices with Spark.

We can use the Kaggle problem: https://www.kaggle.com/c/house-prices-advanced-regression-techniques in order 
to learn pyspark (this is not a real Big Data problem). All of the notebooks are written in Spanish.

## Steps:

- ### Cleaning tasks. 
	In **Preprocesado.ipynb** we can see how to clean our data, transform to numeric, etc.

- ### Exploring.

	In **Exploracion_y_Visualizacion.ipynb** we can find a brief data exploration.

- ### Modeling.

	We have follow three strategies:
	- #### Use log transform in some variables.
		We see this first aproach in **PrimerosModelos.ipynb**.
	- #### Use log transform in the response variable.
 		We see this second aproach in **Modelos_VarObjTrans.ipynb**.
	- #### Select variables.
		We use the previous transform, but we select variables, we can find this in **Modelos_SelVar.ipynb**.