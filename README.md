# Student-Score-Prediction-ML-Project

Live Application link is Below 

https://student-score-prediction-ml-project-mksajmvu3rg2lxmcimzztr.streamlit.app/




# 🎓 Student Score Prediction ML Project

## 📋 Description

The **Student Score Prediction ML Project** is a machine learning–based web application that predicts a student’s exam score based on study-related factors such as the number of study hours and other academic inputs. The main objective of this project is to help students and educators understand the relationship between study time and performance, using simple yet effective regression techniques.

This project demonstrates the use of **Supervised Machine Learning (Regression)** for predictive analytics in education, providing valuable insights into student performance prediction.

---

## 🚀 Features

* 📈 Predicts student exam scores based on input features
* 🧠 Uses a trained **Regression Model** for accurate predictions
* 💻 Interactive web interface built using **Streamlit**
* ⚙️ Real-time user input and instant prediction
* 📊 Simple visualization and data insights

---

## 🧩 Tech Stack

* **Programming Language:** Python
* **Framework:** Streamlit
* **Libraries Used:**

  * Pandas
  * NumPy
  * Scikit-learn
  * Matplotlib / Seaborn
  * Pickle (for model saving/loading)

---

## 🧠 How It Works

1. The user enters study-related inputs such as:

   * Hours Studied
   * Attendance Percentage *(optional if dataset includes it)*
   * Previous Test Scores *(optional)*
2. The app preprocesses the input data.
3. The trained regression model (saved as `.pkl` file) predicts the expected exam score.
4. The predicted score is displayed on the app dashboard in real-time.

---

## ⚙️ Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/student-score-prediction-ml-project.git
   cd student-score-prediction-ml-project
   ```
2. Install all dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

---

## 📈 Model Training (Optional)

If you want to train your own model:

1. Open the `model_training.ipynb` notebook.
2. Load the student dataset (e.g., `student_scores.csv`).
3. Preprocess the data and train using regression algorithms like **Linear Regression**.
4. Save the trained model as a `.pkl` file:

   ```python
   import pickle
   pickle.dump(model, open('student_model.pkl', 'wb'))
   ```

---

## 🖼️ Screenshot (Optional)

*Add a screenshot of your app interface here.*
Example:

```markdown
![App Screenshot](images/screenshot.png)
```

---

## 📚 Future Enhancements

* Add more input features like attendance, test scores, and study materials
* Include data visualization dashboards for performance tracking
* Deploy the app on **Heroku / AWS / Streamlit Cloud**
* Improve prediction accuracy using ensemble or deep learning methods

---

## 👨‍💻 Author

**Developed by:** Om Mankar
**Email:** [ombankar25@gmail.com](mailto:ombankar25@gmail.com)


