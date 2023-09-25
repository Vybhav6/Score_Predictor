# Cricket Inning Score Predictor

## Introduction

Predicting the final score of a cricket inning using machine learning techniques. This project aims to improve team strategies, fan engagement, and data-driven insights in cricket. It aids in player performance evaluation, informs betting and fantasy sports decisions, and enhances media coverage and commentary. Predictions should be seen as probabilities, considering cricket's dynamic nature and external influences.

## Technologies Used

Libraries and Models:
- Pandas
- Numpy
- Streamlit
- Scikit-learn
- XGB
- XGBRegressor
- Pipeline

Environment:
- Jupyter Notebook
- VScode

## Dataset and Data Preprocessing

### Data Collection

Gathering dataset from Kaggle which contains more than 1300+ matches data.

### Data Cleaning

Cleaning unwanted data columns to improve efficiency.

## Data Transformation

- **Feature Scaling:** Normalize or standardize numerical features to bring them to a similar scale, preventing certain features from dominating the analysis or model training.

- **Encoding Categorical Variables:** Convert categorical variables into numerical format using techniques like one-hot encoding or label encoding.

- **Feature Engineering:** Create new features or extract meaningful information from existing features to improve the model's performance.

- **Data Reduction:** Reduce the dimensionality of the dataset to improve computational efficiency and mitigate the curse of dimensionality.

- **Splitting Data:** Divide the dataset into training, validation, and test sets to evaluate the model's performance on unseen data and prevent overfitting.

- **Handling Text and Categorical Data:** Using one-hot encoding to convert them into a format suitable for analysis or model training.

- **Handling Missing Data:** Using Median value to fill out missing values.

### Documentation

Keep track of all preprocessing steps and document any changes made to the original data.

## Exploratory Data Analysis (EDA)

Detail the exploratory analysis conducted using tools like pandas and Jupyter Notebook. Present key insights and visualizations that helped understand the dataset better.

## Model Development

Initially, Random Forest was selected for prediction, but it wasn't accurate enough. XGBRegressor was then used, providing superior predictive performance due to its gradient boosting algorithm, effectively handling complex relationships in data, making it well-suited for accurate regression tasks in various domains.

## Model Evaluation

After completing the model, it was tested with 15+ real-world match data, and the model's predictions were found to be reliable.

## Streamlit App Development

Streamlit was used for creating interactive web applications. The project was deployed using Streamlit Share hosting service due to its user-friendly interface, requiring minimal effort for app creation.

## Conclusion

The creation of a Score Predictor using advanced machine learning techniques and the interactive Streamlit platform represents a significant advancement in sports analytics. This project empowers teams with strategic insights, enhances fan engagement, and highlights the potential of data-driven decision-making in cricket. The convergence of technology and sports offers a valuable tool for cricket enthusiasts, analysts, and teams.

## References

Include citations for any external sources, libraries, or tutorials used during the project.

## Demo

Check out the live demo of the project: [Score Predictor Demo](https://scorepredictor.streamlit.app/)
