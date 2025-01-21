# Graduate Student Admission Project

This repository contains the code and resources for the **Graduate Student Admission Project**, aimed at predicting the likelihood of admission for graduate school applicants based on various factors.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Contributing](#contributing)
- [License](#license)

## Overview
The Graduate Student Admission Project leverages machine learning techniques to predict admission probabilities based on applicant data such as GRE scores, TOEFL scores, undergraduate GPA, research experience, and more. This project is designed to assist admission committees in making data-driven decisions.

## Features
- **Data Preprocessing**: Handles missing values, feature scaling, and one-hot encoding.
- **Machine Learning Models**: Includes multiple algorithms like Linear Regression, Decision Trees, and Random Forest.
- **Feature Importance**: Highlights the most influential factors in admission decisions.
- **Interactive Visualizations**: Provides insights through charts and graphs.

## Tech Stack
- **Programming Language**: Python
- **Libraries**:
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - Jupyter Notebook

## Dataset
The dataset includes the following features:
- GRE Score
- TOEFL Score
- University Rating
- Statement of Purpose (SOP) Strength
- Letter of Recommendation (LOR) Strength
- CGPA (Undergraduate GPA)
- Research Experience (0 or 1)
- Chance of Admission

### Source
[Dataset Link](#) (Add the actual link or source if available)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/graduate-admission-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd graduate-admission-project
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open the main project notebook (e.g., `Graduate_Admission_Analysis.ipynb`).
3. Follow the steps in the notebook to preprocess data, train models, and evaluate performance.

## Model Performance
The following table summarizes the performance of different models used in this project:

## Model Performance

| Model               | Parameters                                           | MSE      | RMSE     | R² Score |
|---------------------|-----------------------------------------------------|----------|----------|------------|
| Linear Regression   | Default parameters                                  | 0.003705 | 0.060866 | 0.818843   |
| Lasso               | alpha=0.1                                           | 0.015120 | 0.122964 | 0.260630   |
| SVR                 | C=10, gamma='scale'                                 | 0.005675 | 0.075333 | 0.722489   |
| Decision Tree       | max_depth=5, criterion='squared_error',             | 0.006486 | 0.080534 | 0.682846   |
| KNN                 | n_neighbors=10                                      | 0.004463 | 0.066803 | 0.781779   |
| Random Forest       | n_estimators=200, max_depth=10, random_state=42     | 0.004228 | 0.065026 | 0.793234   |
| Voting Regressor    | Combination of Linear Regression, Lasso, SVR, etc.  | 0.004194 | 0.064762 | 0.794910   |
| Stacking Regressor  | Combination of Linear Regression, Lasso, SVR, etc.  | 0.004195 | 0.064771 | 0.794849   |

Visualizations of model performance and feature importance can be found in the notebook.

- **Linear Regression** provides a good baseline with an R² Score of 0.818843.
- **Lasso** underperforms relative to other models, with an R² Score of 0.260630.
- **Voting Regressor** and **Stacking Regressor** achieve the best performance, both with an R² Score close to 0.7949.
- **Random Forest** demonstrates strong performance with an R² Score of 0.793234 and RMSE of 0.065026.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

Feel free to reach out with any questions or suggestions!
