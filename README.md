# AML1
# Machine Learning Project 1 - Spring 2024
## Professor Duan's Class

Welcome to the GitHub repository for Machine Learning Project 1 under Professor Duan for the Spring 2024 semester. This project is part of the coursework for students enrolled in Professor Duan's machine learning class. Here, we aim to explore and apply fundamental machine learning concepts on a selected dataset to predict outcomes accurately.

### Project Overview

In this project, we delve into a comprehensive machine learning workflow, starting from data preprocessing, feature engineering, model selection, and finally, to model evaluation and interpretation. Our objective is to apply learned machine learning techniques to a real-world dataset, enhancing our understanding and ability to extract meaningful insights from data.

### Dataset Description

The dataset used in this project is sourced from the National Health and Nutrition Examination Survey (NHANES). It encompasses a wide range of health and nutritional parameters among participants, aiming to predict the occurrence of Myocardial Infarction (MI) based on various health indicators.

### Key Features

- `Income`: Participant's income level
- `Age`: Age of the participant
- `Diastolic`: Diastolic blood pressure
- `Systolic`: Systolic blood pressure
- `Pulse`: Pulse rate
- `BMI`: Body Mass Index
- `HDL`: High-density lipoprotein cholesterol
- `Trig`: Triglycerides
- `LDL`: Low-density lipoprotein cholesterol
- `TCHOL`: Total cholesterol
- `Kidneys_eGFR`: Estimated glomerular filtration rate
- Categorical features including `Sex`, `Race`, `Edu` (Education level), `Diabetes` status, `CurrentSmoker`, `isActive` (physical activity level), and `isInsured` (insurance status).

### Methodology

1. **Data Preprocessing**: Handling missing values, scaling numeric features, and encoding categorical variables.
2. **Feature Engineering**: Investigating and creating new features that might improve model performance.
3. **Model Selection**: Experimenting with various models including k-Nearest Neighbors (kNN) and Logistic Regression.
4. **Hyperparameter Tuning**: Utilizing GridSearchCV for finding the optimal model parameters.
5. **Evaluation**: Using metrics such as Accuracy, ROC AUC Score, Confusion Matrix, and Classification Report for model assessment.

### Installation and Setup

Clone this repository to get started with the project:

```
git clone https://github.com/<your-username>/<repository-name>.git
```

Ensure you have Python installed on your machine along with the necessary libraries:

- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib

You can install these packages using pip:

```
pip install pandas numpy scikit-learn imbalanced-learn matplotlib
```

### Running the Project

Navigate to the project directory and execute the main script to run the project:

```
python main.py
```

### Results

The project concludes with the Logistic Regression model showing a promising ROC AUC Score of 0.791 and an accuracy of 0.757, signifying a strong ability to distinguish between the classes. The model's performance, especially in handling class imbalance, showcases the effectiveness of the applied machine learning techniques.

### Contributing

We welcome contributions and suggestions to improve this project. Please feel free to fork the repository, make changes, and submit pull requests.

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

### Acknowledgments

- Professor Duan, for providing guidance and insights throughout the project.
- The NHANES study, for making their valuable dataset publicly available for educational purposes.

---

For any queries or further information, please contact the project contributors or Professor Duan directly.

**Happy Learning!**