# Ml-Student-performance-prediction
# 🎓 Student Performance Prediction

This project uses **Linear Regression** to predict student academic performance based on various factors such as previous scores, study hours, attendance, and extracurricular activities.

## 📌 Objective

The goal is to build a simple and interpretable machine learning model that can help identify key factors influencing student success and predict final scores.

## 📊 Dataset

The dataset includes the following features:

- **Previous Score**
- **Study Hours**
- **Attendance Rate**
- **Extracurricular Activities (Yes/No)**
- **Final Score (Target)**

Categorical features were encoded using `LabelEncoder`, and numerical features were scaled using `StandardScaler`.

## 🔧 Technologies Used

- Python
- Pandas & NumPy (data preprocessing)
- scikit-learn (modeling and evaluation)
- Matplotlib & Seaborn (visualizations)
- Google Colab (notebook environment)

## ⚙️ Model Workflow

1. **Load & clean the dataset**
2. **Encode categorical features**
3. **Scale numerical features**
4. **Split data into train/test sets**
5. **Train Linear Regression models**
   - Simple model (using only `Previous Score`)
   - Multiple feature model (using all predictors)
6. **Evaluate using:**
   - Mean Squared Error (MSE)
   - R² Score
7. **Analyze feature importance**

## 📈 Evaluation

The multiple linear regression model outperformed the single-feature model, indicating that student performance is influenced by several factors, not just previous scores.

## 📁 Folder Structure

student-performance/
│
├── student_performance.ipynb # Main notebook
├── student_data.csv # Dataset file
├── README.md # Project overview
└── requirements.txt # Dependencies (optional)


## 🚀 How to Run

1. Open `student_performance.ipynb` in Google Colab or Jupyter Notebook.
2. Run each cell step by step.
3. Upload `student_data.csv` if required.
4. Review the model output and visualizations.

## 🙌 Contribution

Suggestions or improvements are welcome! Feel free to fork this repo and submit a pull request.

## 📄 License

This project is licensed under the MIT License.
