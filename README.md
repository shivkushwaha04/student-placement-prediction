# Student Placement Prediction

A simple machine learning project that predicts whether a student will get placed based on their **CGPA** and **IQ**, using **Logistic Regression**.

## 📊 Dataset

- Toy dataset with **100 records**
- Features (independent variables): `cgpa`, `iq`
- Target (dependent variable): `placement` (0 = Not Placed, 1 = Placed)

## 🛠️ Tech Stack

- Python
- NumPy, Pandas
- Matplotlib
- Scikit-learn
- Mlxtend (for decision boundary visualization)

## 🔄 Workflow

1. **Preprocessing & EDA** — Load and inspect the dataset
2. **Feature Selection** — Extract `cgpa` and `iq` as input, `placement` as output
3. **Train-Test Split** — 90% training, 10% testing
4. **Feature Scaling** — Standardized using `StandardScaler`
5. **Model Training** — Logistic Regression
6. **Evaluation** — Accuracy score on test data
7. **Visualization** — Decision boundary plotted using `mlxtend`
8. **Deployment Prep** — Trained model saved as `model.pkl` using `pickle`

## 📈 Results

- Achieved **80% accuracy** on the test set
- Decision boundary clearly separates placed vs. not-placed students based on CGPA and IQ

## 📁 Project Structure

```
├── placement.csv           # Dataset
├── placement_prediction.ipynb   # Main notebook
├── model.pkl                # Trained model (pickled)
└── README.md
```

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/student-placement-prediction.git
   ```
2. Install dependencies
   ```bash
   pip install numpy pandas matplotlib scikit-learn mlxtend
   ```
3. Open `placement_prediction.ipynb` in Jupyter Notebook / Google Colab and run the cells

## 🔮 Future Improvements

- Try other classification algorithms (SVM, Decision Tree, Random Forest)
- Add cross-validation for more robust evaluation
- Use a larger, real-world dataset
- Build a simple web app (Flask/Streamlit) to deploy the model

## 📝 Note

This is a **beginner/learning project** built on a toy dataset for practicing the end-to-end ML workflow (EDA → preprocessing → training → evaluation → deployment prep).
