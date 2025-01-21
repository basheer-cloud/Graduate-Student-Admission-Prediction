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

| Model                | R² Score | MAE   | RMSE  |
|----------------------|----------|-------|-------|
| Linear Regression    | 0.84     | 0.03  | 0.05  |
| Decision Tree        | 0.80     | 0.04  | 0.06  |
| Random Forest        | 0.86     | 0.02  | 0.04  |

Visualizations of model performance and feature importance can be found in the notebook.

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

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to reach out with any questions or suggestions!
