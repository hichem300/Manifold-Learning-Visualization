
# Manifold Learning & Visualization

In this project, we will be exploring different techniques for visualizing high-dimensional data in two dimensions. 

The first part of the project will focus on the Swiss-roll dataset, where we will generate 2000 points using the function datasets.make_swiss_roll. We will then apply Principal Component Analysis (PCA) to reduce the dataset to two dimensions and plot the data. Next, we will apply Local Linear Embedding (LLE) with 5 neighbors and print the error. We will change the number of neighbors from 2 to 15 and plot the error line to determine the best number of neighbors. 

We will also use Multi-Dimensional Scaling (MDS) to project the dataset in two dimensions and compare the result with the previous techniques. Finally, we will apply t-SNE model to the same dataset and project it in two dimensions, followed by a conclusion on the best model.

In the second part of this project, we will import the digit dataset containing only six classes and analyze the results by explaining the models. We will then use a classification model, such as Decision Tree, on all the projections and compute the errors. Finally, we will compute the quality of models and highlight the gain. 

## Software and Libraries

This project uses the following software and Python libraries:

- Python 3.11.2
- NumPy
- pandas
- matplotlib
- scikit-learn

