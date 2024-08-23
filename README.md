# Student Performance Dataset

![8741017](https://github.com/user-attachments/assets/094667d4-fd10-4c02-a215-90a549b4dc86)

## Overview

This dataset contains the performance of students in exams, with associated demographic data and other relevant factors. The dataset includes various attributes that provide insights into students' academic performance in subjects such as math, reading, and writing. It can be used for educational analysis, performance prediction, and demographic impact studies.

## Dataset Description

The dataset consists of **1000** entries with **8** features:

- **gender**: Gender of the student (`male`, `female`)
- **race_ethnicity**: The ethnic group of the student (`group A`, `group B`, `group C`, `group D`, `group E`)
- **parental_level_of_education**: The highest level of education attained by the student's parents (`some high school`, `high school`, `some college`, `associate's degree`, `bachelor's degree`, `master's degree`)
- **lunch**: Type of lunch the student had (`standard`, `free/reduced`)
- **test_preparation_course**: Whether the student completed a test preparation course (`none`, `completed`)
- **math_score**: The student's score in the math exam (integer, 0-100)
- **reading_score**: The student's score in the reading exam (integer, 0-100)
- **writing_score**: The student's score in the writing exam (integer, 0-100)

## File Structure

- **stud.csv**: The main dataset file in CSV format.

## Data Preview

Below is a preview of the dataset's first few rows:

| gender | race_ethnicity | parental_level_of_education | lunch        | test_preparation_course | math_score | reading_score | writing_score |
|--------|----------------|-----------------------------|--------------|-------------------------|------------|---------------|---------------|
| female | group B        | bachelor's degree           | standard     | none                    | 72         | 72            | 74            |
| female | group C        | some college                | standard     | completed               | 69         | 90            | 88            |
| female | group B        | master's degree             | standard     | none                    | 90         | 95            | 93            |
| male   | group A        | associate's degree          | free/reduced | none                    | 47         | 57            | 44            |
| male   | group C        | some college                | standard     | none                    | 76         | 78            | 75            |

## Usage

This dataset can be used for various purposes, including but not limited to:

- **Educational Analysis**: Understanding the impact of different factors on student performance.
- **Predictive Modeling**: Building models to predict student scores based on demographic data.
- **Statistical Studies**: Analyzing correlations between parental education level, test preparation, and student scores.

## Project Structure

- **artifacts/**: Stores intermediary and final data/results used or generated during the project.
- **notebook/**: Jupyter notebooks used for data exploration, feature engineering, model training, and analysis.
- **src/**: Contains the core source code, including custom modules and utility functions used in the project.
- **templates/**: HTML templates for the web application.
- **app.py**: The main Python script for running the web application that allows users to interact with the trained machine learning models.
- **requirements.txt**: Lists the Python dependencies required to run the project.
- **setup.py**: Script to install the package and its dependencies.

## Packages Required

To run this project and analyze or visualize this dataset, you might need the following Python packages:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`
- `Flask`
- `dill`
- `-e .` (to install the project in editable mode)

You can install these dependencies by running:

```bash
pip install -r requirements.txt
```

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Syed-Irfan-1165/Machine-Learning-Project.git
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the web application**:
    ```bash
    python app.py
    ```

4. **Explore the notebooks**:
   - Navigate to the `notebook/` directory to view Jupyter notebooks that demonstrate data preprocessing, model training, and evaluation.

## Notebooks

The `notebook/` directory contains detailed Jupyter notebooks that cover:
- **Data Exploration**: Understanding the dataset with visualizations and summary statistics.
- **Feature Engineering**: Creating and selecting features for model training.
- **Model Training**: Building and training machine learning models.
- **Model Evaluation**: Assessing model performance using various metrics.

3. **Perform analysis**:
    - Use various statistical and machine learning techniques to analyze the data.
    - Example: Correlation between `parental_level_of_education` and `math_score`.

## Contributing

If you would like to contribute to this project, please submit a pull request or raise an issue.
