<b><h1>Problem Description:</h1></b>

In this repository, you will find a solution to a problem involving data analysis and machine learning applied to a dataset containing information about various chemical compounds. The problem is outlined below:

<b>Dataset</b>:
I have already uploaded the data set as well. The dataset is tabulated into rows, with each row representing a compound. Columns include common name, molecular weight, critical temperature (K), acentric factor, and normal boiling point (K).

<b><h2>Task:</h2></b>

(a) <b>Data Analysis:</b>

Extract the boiling points and molecular weights from the dataset.
Plot the normal boiling point against the molecular weight and fit a straight line through the data.
Calculate the R2 value to evaluate the fit.

(b) <b>Machine Learning:</b>

Select a random subset of 100 compounds from the dataset to form a training set.
Create a 100 × 3 matrix X, where each row corresponds to a training example, with columns representing the molecular weight, acentric factor, and a bias term.
Create a column vector y containing the expected reduced boiling point (Tb/Tc) for each training example.
Use the formula 𝜽 = (𝑿𝑻𝑿)^−1 𝑿𝑻𝒚 to calculate the coefficients 𝜃0, 𝜃1, and 𝜃2 for the linear regression model.

(c) <b>Neural Network:</b>

Extract input data (molecular weight and acentric factor) and target data (reduced boiling point).
Develop and train a neural network using only 10% of the data.
Experiment with changing the number of layers and observe the effects on the model's performance.
Note: The dataset contains additional data which can be utilized for further exploration and analysis.

For detailed solutions and implementations, please refer to the provided code files in this repository.

<b>Instructions:</b>

1. Clone this repository to your local machine.
2. Download the dataset from the provided link.
3. Execute the code files to analyze the data and solve the problem as described 
