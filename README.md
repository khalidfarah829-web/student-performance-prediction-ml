# 📈 Student Performance Prediction Using Machine Learning

A supervised **Machine Learning** project designed to analyze and predict students' final academic scores based on behavioral and academic metrics. By leveraging regression algorithms, this system provides actionable insights for educational institutions to proactively identify students needing additional scholastic support.

---

## 🚀 Key Features

- **📊 Comprehensive Data Pipeline:** Features automated ingestion of structured behavioral data (`student_data.csv`) including Study Hours, Attendance records, and Previous Scores.
- **🤖 Dual-Model Predictive Architecture:** Implements and compares two structural core algorithms:
  - **Linear Regression:** For modeling straightforward, continuous numeric correlations.
  - **Decision Tree Regressor:** For mapping non-linear complex feature branching and variance tracking.
- **📉 Performance Evaluation:** Tracks model precision dynamically utilizing Mean Absolute Error (MAE) benchmarks.
- **🎨 Interactive Visualizations:** Integrates Matplotlib matrix plots mapping **Actual vs. Predicted Final Scores** to showcase model accuracy visually.

---

## 🛠️ Tech Stack & Libraries Used

- **Language:** Python
- **Core ML Framework:** Scikit-Learn (`sklearn`)
- **Data Manipulation:** Pandas & NumPy
- **Data Visualization:** Matplotlib

---

## 📖 How to Run the Project

1. Ensure Python 3.x and the required packages are installed:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
