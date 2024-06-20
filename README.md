# Machine Learning: Optimization with Random Exploration

This repository contains a project focused on evaluating how random exploration can be used for quick and practical optimization of a machine learning model designed to predict whether a car will be sold based on variables such as mileage, model year, and price. The project utilizes `RandomizedSearchCV` to test random values within a specified range for the hyperparameters `max_depth`, `min_samples_split`, `min_samples_leaf`, and `criterion` of a `DecisionTreeClassifier` model. Additionally, the project explores the use of `GridSearchCV` and cross-validation to optimize the model while balancing computational resource consumption.

## Project Overview
The goal of this project is to demonstrate how random exploration can be an efficient method for hyperparameter optimization in machine learning models. By comparing exhaustive and random searches, the project aims to find the best model with optimized hyperparameters without overusing computational resources.

## Course Details
This project was completed as part of the Machine Learning course on Alura. For more information about the course, visit [Alura](https://cursos.alura.com.br/formacao-machine-learning-v64177).

## Objectives Achieved
- Explore parameter spaces randomly.
- Use `RandomizedSearchCV` for efficient search optimization.
- Compare exhaustive search with random search.
- Perform optimization with and without cross-validation when applicable.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

## Project Structure
The directory structure of the project is as follows:
```
machine-learning-otimização-com-exploração-aleatória/
│   project-1-data.csv
│   project-1.ipynb
│   README.md
```

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/goosekiing/machine-learning-otimizacao-com-exploracao-aleatoria.git
   ```
2. Navigate to the project directory:
   ```sh
   cd machine-learning-otimizacao-com-exploracao-aleatoria
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook project-1.ipynb
   ```

## Learn More
To learn more about hyperparameter optimization and machine learning, visit the course page on [Alura](https://cursos.alura.com.br/formacao-machine-learning-v64177).

Feel free to explore, modify, and use this project as a foundation for your own machine learning projects!

## Language
The language used in this project is Brazilian Portuguese (pt-br).
