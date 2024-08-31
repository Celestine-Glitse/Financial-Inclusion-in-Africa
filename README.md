# Financial Inclusion in Africa - Machine Learning Classification Project

## Project Overview

This project aims to predict which individuals in Kenya, Rwanda, Tanzania, and Uganda are most likely to have or use a bank account. The ability to access bank accounts is a critical indicator of financial inclusion and economic development. This project uses machine learning techniques to provide insights into the factors that drive financial security across these countries.

## Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Features](#features)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Data

The dataset used in this project contains information on individuals across Kenya, Rwanda, Tanzania, and Uganda. The key target variable is `bank_account`, which indicates whether an individual has access to or uses a bank account.

### Key Variables:
- **Country**: The country of residence.
- **Year**: The year of data collection.
- **Unique ID**: An identifier for each individual.
- **Education Level**: The education level of the respondent.
- **Age of Respondent**: The age of the individual.
- **Job Type**: The type of job the respondent holds.
- **Marital Status**: The marital status of the individual.
- **Gender**: The gender of the individual.

## Features

The project employs various features, including demographic, socioeconomic, and geographic variables, to predict financial inclusion.

## Models Used

This project explores various machine learning models, including:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier

## Evaluation Metrics

The following metrics were used to evaluate the models:
- **Accuracy**: The proportion of correct predictions.
- **Mean Absolute Error (MAE)**: The average absolute differences between the predicted and actual values. MAE clearly indicates how close predictions are to the actual outcomes on average, with lower values indicating better performance.
- **Confusion Matrix**: A matrix to visualize the performance, showing True Positives, True Negatives, False Positives, and False Negatives.
- **Classification Report**: Includes precision, recall, and F1-score for each class.

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/financial-inclusion-africa.git
cd financial-inclusion-africa
pip install -r requirements.txt
```

## Usage

1. Preprocess the data using the provided scripts.
2. Train the machine learning models.
3. Evaluate model performance using the provided metrics.

## Results

- The models achieved significant accuracy in predicting financial inclusion across the four countries.
- The Random Forest model showed the highest performance, with accuracy reaching up to 85%.
- Insights were drawn regarding the impact of education, age, and job type on financial inclusion.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Reference
1- Zindi - Financial Inclusion in Africa
2- ChatGPT
3- Google
