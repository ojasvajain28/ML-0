


# EMNIST Data Sampling and Dimensionality Reduction

This repository contains code that demonstrates data sampling and dimensionality reduction techniques on the EMNIST dataset. The code provides examples of random sampling without replacement, random sampling with replacement, and dimensionality reduction using PCA and t-SNE.

## Table of Contents
- [Introduction](#introduction)
- [Data Sampling](#data-sampling)
- [Dimensionality Reduction](#dimensionality-reduction)
- [Instructions](#instructions)
- [License](#license)

## Introduction
The EMNIST (Extended MNIST) dataset is a collection of handwritten characters. It includes both uppercase and lowercase letters, as well as digits and symbols. The goal of this code is to showcase how to perform data sampling and dimensionality reduction techniques on the EMNIST dataset.

## Data Sampling
The code provides examples of two types of data sampling techniques: random sampling without replacement and random sampling with replacement.

- Random Sampling Without Replacement: The code randomly selects a sample of size 10 from the original dataset without replacement. It ensures that each selected sample is unique and not repeated.

- Random Sampling With Replacement: The code randomly selects a sample of size 1% of the entire dataset with replacement. This means that each selected sample has the possibility of being selected multiple times.

## Dimensionality Reduction
The code also demonstrates two dimensionality reduction techniques: Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE).

- Principal Component Analysis (PCA): The code performs PCA to reduce the dimensionality of the dataset to two components. It first standardizes the features using `StandardScaler` to ensure they have zero mean and unit variance. Then, it applies PCA using `PCA` from the scikit-learn library. The results are visualized using a scatter plot.

- t-Distributed Stochastic Neighbor Embedding (t-SNE): The code applies t-SNE to reduce the dimensionality of the dataset to two components. It follows a similar process as PCA, but instead of linear transformations, t-SNE focuses on preserving the local structure of the data. The resulting two-dimensional embeddings are visualized using a scatter plot.

## Instructions
To run the code and replicate the results, follow these steps:

1. Clone the repository or download the code files.

2. Ensure you have the necessary dependencies installed: Pandas, NumPy, scikit-learn, and Matplotlib. You can install them using the following command:
   ```
   pip install pandas numpy scikit-learn matplotlib
   ```

3. Download the EMNIST dataset and place it in the same directory as the code. The dataset should be named "emnist-byclass-test.csv".

4. Run the code in a Python environment. The main script is provided as a Jupyter Notebook file (`.ipynb`), which you can open and execute cell by cell.

5. Observe the results of data sampling and dimensionality reduction. The code will display the randomly selected samples and visualize the reduced-dimensional embeddings.

## License
This code is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code in accordance with the terms of the license.

Feel free to explore and experiment with the code to gain insights into data sampling and dimensionality reduction techniques on the EMNIST dataset.

If you have any questions or suggestions, feel free to open an issue or contact .
