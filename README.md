# Titanic - Machine Learning from Disaster 🚢

This project is my solution to the legendary **Titanic ML competition** on Kaggle. It is the best starting point for diving into machine learning competitions and exploring the Kaggle platform.

The competition goal is simple: **use machine learning to predict which passengers survived the Titanic shipwreck**.

---

## 🚀 Project Highlights

- **Explored Feature Engineering:** Extracted titles, handled missing values, encoded categorical variables, and scaled numerical features.
- **Tried Multiple Models:** 
  - Classical algorithms like Logistic Regression, Decision Tree, and Random Forest.
  - Advanced ensemble methods like Gradient Boosting, AdaBoost, XGBoost, and LightGBM.
  - Trained a simple **neural network** using PyTorch.
- **Optimized Models:** Fine-tuned hyperparameters to achieve the best results.

---

## 🛠️ Steps in the Solution

### 1. Data Preprocessing
- **Handled Missing Values:** 
  - Imputed missing values for `Age` using medians based on `Pclass` and `Sex`.
  - Filled missing `Embarked` values with the mode.
  - Imputed missing `Fare` values with the median.
- **Dropped Irrelevant Features:** Excluded columns like `Cabin` and `Ticket` for simplicity.

### 2. Feature Engineering
- **Extracted Titles from Names:** Grouped rare titles as "Rare".
- **Encoded Categorical Variables:** Converted `Sex` and `Embarked` to numeric values.
- **Retained Scaled Numerical Features:** Kept `Age` and `Fare` as floating-point values.

### 3. Model Training and Evaluation
- **Models Used:**
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - AdaBoost
  - XGBoost
  - LightGBM
  - K-Nearest Neighbors (KNN)
  - Neural Network (PyTorch)
- **Best Models Based on Validation Accuracy:**
  - **Random Forest**: 82.72%
  - **Gradient Boosting**: 82.58%
  - **Logistic Regression**: 82.02%
- **Neural Network:** Achieved a validation accuracy of 77%.

---

## 📊 Results

| Model                   | Validation Accuracy |
|-------------------------|---------------------|
| Random Forest           | 82.72%             |
| Gradient Boosting       | 82.58%             |
| Logistic Regression     | 82.02%             |
| Neural Network (PyTorch)| 77.00%             |
| K-Nearest Neighbors     | 66.14%             |

---

## 🚀 How to Run

1. Clone this repository:
   ```git clone https://github.com/<your-username>/Titanic-Kaggle-Competition```
   ```cd Titanic-Kaggle-Competition```
2. Install dependencies:
    ```pip install -r requirements.txt```
3. Open the Jupyter notebook
    ```jupyter notebook notebook.ipynb```
4. Run the notebook to preprocess data, train models, and generate predictions.

---

🤝 Acknowledgments

Special thanks to Kaggle for hosting this challenge and providing such a fantastic learning opportunity.

---

🔗 Links
	•	Kaggle Competition: Titanic - Machine Learning from Disaster
	•	GitHub Repository: Titanic-Kaggle-Competition

---

📌 Future Plans
	•	Experiment with more advanced neural network architectures.
	•	Explore feature selection techniques to simplify the dataset further.

---