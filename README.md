🪨 Sonar Rock vs Mine Prediction

A simple machine learning project using Logistic Regression to classify whether an object is a "Rock" or a "Mine" based on sonar signals.

---

📊 Dataset

- Source: (https://drive.google.com/file/d/1pQxtljlNVh0DHYg-Ye7dtpDTlFceHVfa/views)
- 208 samples, 60 features.
- Label: `Rock (R)` or `Mine (M)`.

---

🧠 ML Pipeline

- **Preprocessing**: Dataset is read and split into features and labels.
- **Train-test split**: 90% training, 10% testing using `stratify` to preserve label balance.
- **Model**: Logistic Regression (`sklearn.linear_model.LogisticRegression`)
- **Evaluation**: Accuracy on both train and test sets.

---

📈 Results

- ✅ Training Accuracy: 83.4%
- ✅ Test Accuracy: 76.1%
- Logistic Regression performed well without tuning on this dataset.


---

🛠️ Tech Stack

- Python
- Google Colab
- Scikit-learn
- Pandas, NumPy

---

🧪 How to Run

1. Clone the repo
2. Open `SONAR Rock and Mine Prediction.ipynb` in Jupyter/Colab
3. Run all cells

---

🙋‍♂️ Author

- Sanjana Nagineni
- [GitHub](https://github.com/sanjananagineni25)

🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Try other models (Random Forest, SVM)
- Deploy using Streamlit or Flask


