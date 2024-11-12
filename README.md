# N7-classification-project

This project is a classification project developed at the engineering school ENSEEIHT in 2024 by Ruddy KINSICLOUNON and Galatée MARCQ. The project aims to classify different types of fruits using various classification methods, both supervised and unsupervised. The classification is performed before and after Principal Component Analysis (PCA) and normalization.

## Project Overview

The goal of this project is to classify different types of fruits based on a dataset containing images of fruits. The dataset includes 898 images of seven different types of dates: Barhee, Deglet Nour, Sukkary, Rotab Mozafati, Ruthana, Safawi, and Sagai. A total of 34 features, including morphological characteristics, shape, and color, were extracted from these images using image processing techniques.

## Methods Used

### Supervised Learning Methods
- **Naive Bayes**
- **K-Nearest Neighbors (KNN)**

### Unsupervised Learning Methods
- **K-Means Clustering**
- **Gaussian Mixture Models (GMM)**

### Data Preprocessing
- **Normalization**: Min-Max Scaler, Standard Scaler, Max Abs Scaler
- **Principal Component Analysis (PCA)**: Dimensionality reduction to 2D and 3D

## Project Structure

- **Data Loading and Preprocessing**: Loading the dataset, encoding labels, splitting the data into training and test sets, and applying normalization.
- **Supervised Learning**: Training and evaluating supervised learning models, calculating confusion matrices, and accuracy scores.
- **Unsupervised Learning**: Applying clustering methods, visualizing clusters, and calculating performance scores.
- **PCA**: Reducing the dimensionality of the data and visualizing the results.
- **Comparison**: Comparing the performance of different classification methods before and after PCA and normalization.

## Results

The project includes detailed analysis and comparison of the performance of different classification methods. Confusion matrices and accuracy scores are used to evaluate the models. The results are visualized using various plots to provide insights into the effectiveness of each method.

## How to Run

1. **Install Dependencies**: Ensure you have the required Python libraries installed. You can install them using the following command:
    ```bash
    pip install numpy pandas scikit-learn matplotlib seaborn
    ```

2. **Run the Notebook**: Open the `ProjetFruits.ipynb` notebook in Jupyter Notebook or any compatible IDE (e.g., PyCharm) and execute the cells sequentially.

## Authors

- **Ruddy KINSICLOUNON**
- **Galatée MARCQ**

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.