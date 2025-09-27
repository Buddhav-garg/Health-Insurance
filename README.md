# Healthcare Insurance Expenses Project

This project uses machine learning to estimate healthcare insurance expenses. By analyzing a dataset of patient information, a Random Forest model is trained to predict medical costs based on various factors like age, BMI, and smoking habits. The goal is to provide a predictive tool that can assist individuals, healthcare providers, and insurers in making more informed financial decisions.

---

### Key Metrics and Results

* **Model**: Random Forest Regressor
* **Dataset Size**: 1,337 data points
* **Duplicate Entries Removed**: 1
* **Missing Values**: 0
* **Performance Evaluation**: 10-fold cross-validation was used to evaluate the model.
* **Root Mean Squared Error (RMSE) Standard Deviation**: 586.88

---

### How the Model Works

1.  **Data Preprocessing**: The raw data was cleaned by removing a duplicate entry. Categorical features like `sex`, `smoker`, and `region` were converted into a numerical format suitable for machine learning models using `LabelEncoder` and one-hot encoding.

2.  **Data Splitting**: The cleaned dataset was divided into an 80% training set and a 20% testing set to ensure a robust and reliable analysis.

3.  **Model Training and Prediction**: A Random Forest Regressor was trained on the training data. The model then made predictions on the test set, providing a clear comparison between the predicted and actual charges.

---

### Usage

This project's code is available in the `Healthcare_Insurance_Expenses.ipynb` Jupyter Notebook.
