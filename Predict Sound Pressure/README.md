
# Predicting Airfoil Sound pressure using Tensorflow
[![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org/) [![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/) [![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](http://numpy.org)


**Probelm:**  
To predict the sound pressure in decibels from different sizes of NACA 0012 airfoils at various wind tunner speeds and angles of attack.

**Data Information:**
The NASA data set comprises different size NACA 0012 airfoils at various wind tunnel speeds and angles of attack. The span of the airfoil and the observer position were the same in all of the experiments.  

**Atrribute Information:**
This problem has the following **independant** variables:
* Frequency, in Hertzs.
* Angle of attack, in degrees.
* Chord length, in meters.
* Free-stream velocity, in meters per second.
* Suction side displacement thickness, in meters.

**Target variable:**
* Scaled sound pressure level, in decibels. 

**Running the code:**
* Download the notebook and the dataset *airfoil_self_noise.dat* and run it in your local broswer.


**Methods**  
The dataset comprises of 5 features so any dimensionaly reduction is not necessary. exploratory data analysis includes *pairplot*, *correlation matrix* and *feature trend inspection* have been performed. Multivariate Regression model is implemented using TensorFlow.








### Feature Pairplot
![Pair plot](https://github.com/ashwin4ever/Tensorflow_Projects/blob/main/Predict%20Sound%20Pressure/airfoil_pairplot.png)  


<br>

### Line of best fit
![Best Fit](https://github.com/ashwin4ever/Tensorflow_Projects/blob/main/Predict%20Sound%20Pressure/airfoil_bestfit.png)
























