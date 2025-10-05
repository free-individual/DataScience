# Exploratory Data Analysis of Iris Dataset.
![Python](https://img.shields.io/badge/python-3.13.3-FF320A)

## Description

This project explores the classic Iris dataset, starting with an exploratory data analysis (EDA) and concluding with the development of a predictive classification model.

### Part 1: Exploratory Data Analysis
- **Notebook:** [`Iris EDA.ipynb`](./Iris%20EDA.ipynb)
- **Description:** An initial analysis to visualize the data, understand feature distributions, and identify relationships between the flower species. It was concluded that 'Setosa' species is linearly seperable from the other two.

<img src="./Assets/PetalWidth%20vs.%20SepalWidth.png" alt="Seaborn Scatter Plot of Iris Data: Petal width against Sepal width" width="600">

<img src="./Assets/PetalLength%20vs.%20SepalLength.png" alt="Seaborn Scatter Plot of Iris Data: Petal Length against Sepal Length" width="600">

### Part 2: Predictive Model
- **Notebook:** [`Iris Prediction.ipynb`](./Iris%20Prediction.ipynb)
- **Description:** A machine learning model using Logistic Regression is built and evaluated. The model achieves 100% accuracy on the test set.

## Technologies Used
* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Getting Started

### Pre Requisites
- Python 3.8 or higher
- Pip package manager
- Jupyter Notebook

### Installation
1. Clone repository
    ```sh
    git clone [https://github.com/free-individual/DataScience.git](https://github.com/free-individual/DataScience.git)

2. Navigate to project directory
    ```sh
    cd DataScience/Iris EDA

3. Install the required libraries from requirements.txt
    ```sh
    pip install -r requirements.txt

### Usage
4. Launch Jupyter Notebook from terminal
    ```sh
    jupyter notebook

5. Open the Iris EDA.ipynb file and run the cells.
