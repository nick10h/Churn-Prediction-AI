# Churn Prediction AI

## Overview

This repository contains a machine learning project aimed at predicting customer churn for a subscription-based service. The project utilizes various techniques, including exploratory data analysis (EDA), feature engineering, and model development, to build a predictive model capable of identifying customers likely to churn.
## Table of Contents

- [Project Structure](#project-structure)
- [Data Description](#data-description)
- [Installation](#installation)
- [Usage](#usage)
- [Model Development](#model-development)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

The repository follows a structured approach to organize the project components:


- `.ipynb_checkpoints/`: Contains Jupyter Notebook checkpoint files.
- `catboost_info/`: Directory for storing CatBoost model-related information.
- `Data Description.pdf`: A PDF document detailing the dataset's features and attributes.
- `EDA.ipynb`: Jupyter Notebook for performing exploratory data analysis.
- `Feature Selection.ipynb`: Jupyter Notebook for feature selection techniques.
- `churn_model.ipynb`: Jupyter Notebook for developing and evaluating the churn prediction model.
- `client_data.csv`: CSV file containing raw client data.
- `engineered_data.csv`: CSV file containing data after preprocessing and feature engineering.
- `price_data.csv`: CSV file containing pricing-related information.

## Data Description

The dataset comprises several features that describe customer behavior and demographics. A detailed explanation of each feature is available in the `Data Description.pdf` file.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/nick10h/Churn-Prediction-AI.git
cd Churn-Prediction-AI
```

2. Create a Virtual Environment:

  ```bash
  python -m venv venv
  ```

3. Activate the virtual environment:

->On Windows:
```bash
.\venv\Scripts\activate
```

->On macOS/Linus:
```bash
source venv/bin/activate
```
4. Install the dependecies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn catboost
```
## Usage

After setting up the environment, you can start by exploring the data and building the model:

1. Open the `EDA.ipynb` notebook to perform exploratory data analysis.
2. Proceed to `Feature Selection.ipynb` to apply feature selection techniques.
3. Finally, use `churn_model.ipynb` to develop and evaluate the churn prediction model.

## Model Development

The project employs the following steps in model development:

1. **Data Preprocessing:** Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Exploratory Data Analysis (EDA):** Visualizing data distributions and relationships between features.
3. **Feature Engineering:** Creating new features to improve model performance.
4. **Model Training:** Using algorithms like CatBoost to train the model.
5. **Model Evaluation:** Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.

