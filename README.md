# K-Nearest Neighbors (KNN) Tutorial

A beginner-friendly introduction to machine learning using the K-Nearest Neighbors algorithm and the famous iris dataset.

## Overview

This tutorial demonstrates how to build your first machine learning classifier using KNN. You'll learn to classify iris flower species based on their measurements through a step-by-step implementation.

## What You'll Learn

- How the KNN algorithm works conceptually
- Data preparation and train/test splitting
- Model training and evaluation
- Visualization techniques for ML data
- Understanding model performance metrics
- Impact of hyperparameter tuning (k value)
- Making predictions on new data

## Requirements

- Python 3.8+
- Required libraries (install via pip):
  ```bash
  pip install pandas numpy matplotlib scikit-learn seaborn jupyter
  ```

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/Daisy-Faith-Auma/knn-tutorial.git
   cd knn-tutorial
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv knn-env
   source knn-env/bin/activate  # On Windows: knn-env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook knn_tutorial.ipynb
   ```

## Dataset

This tutorial uses the [iris dataset](https://archive.ics.uci.edu/ml/datasets/iris), which contains measurements of 150 iris flowers across three species (setosa, versicolor, virginica).

## Tutorial Structure

1. **Data Loading and Exploration** - Understanding the iris dataset
2. **Data Visualization** - Plotting species clusters
3. **Data Preparation** - Feature/target separation and train/test split
4. **Model Training** - Building the KNN classifier
5. **Model Evaluation** - Accuracy assessment and confusion matrix
6. **Algorithm Analysis** - Visualizing KNN decision-making process
7. **Hyperparameter Tuning** - Testing different k values
8. **Practical Application** - Making predictions on new data

## Results

The tutorial achieves 95-100% accuracy on the iris dataset, demonstrating the effectiveness of KNN for well-separated data clusters.

## Technologies Used

- **Python** - Programming language
- **scikit-learn** - Machine learning library
- **pandas** - Data manipulation
- **matplotlib/seaborn** - Data visualization
- **numpy** - Numerical computing
- **Jupyter** - Interactive development environment

## Contributing

This is an educational tutorial. Feel free to fork and modify for your own learning purposes.

## License

This project is open source and available under the [MIT License](LICENSE).
