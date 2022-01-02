# DiabetesPrediction #
A notebook on the "Pima Indians Diabetes Database" from the National Institute of Diabetes and Digestive and Kidney Diseases [Link](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

# Contents #
### 1. Data Inspection ###
  - Calculated the "Five Number Summary" using `describe()` function.
  - Displayed the data information by `info()` function.
  
### 2. Data Cleaning ###
- Finding the missing and inconsistent values using:-
  1. Five Number Summary
  2. `seaborn.heatmap() function`
- Choosing The best way to replace them for each column using `hist()` function.
- Replacing them using `fillna()` with the `mean()` and `median()` functions. 

### 3. Finding Correlation ###
- Calculated "Pearson's Correlation Coefficient" and plotted it using `seaborn.heatmap()` function, To check for any **not needed** features.

### 4. Normalization ###
- Used `StandardScaler()` to normalize the data using the **Z-Score** method.

### 5. KNN Algorithm ###
- Found the best value for **K** by looping in a range (1 ==> 27).
- Best value of **K** is 9 with accuracy of **80.51948 %**
- Built the KNN model using `K = 9`.
- Calculated the "Confusion Matrix" using `metrics.confusion_matrix()` function, Then plotted it using `seaborn.heatmap()` function.
