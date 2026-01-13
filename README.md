# 🌸 Iris Flower Classification using Machine Learning & Streamlit

This project is a **Machine Learning web application** that predicts the species of an Iris flower based on its measurements.  
The model is trained using the **Iris dataset** and deployed using **Streamlit** for interactive user input.

---

## 📌 Project Overview

The application predicts the Iris flower species:
- **Setosa**
- **Versicolor**
- **Virginica**

based on:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

A **Random Forest Classifier** is used for prediction.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  
- Jupyter Notebook  

---

## 📊 Dataset

- **Iris Dataset** (built-in from `sklearn.datasets`)
- Contains 150 samples with 4 features and 3 target classes.

---

## ⚙️ How the Model Works

1. Load the Iris dataset  
2. Convert it into a Pandas DataFrame  
3. Train a **Random Forest Classifier**  
4. Take user input using Streamlit sliders  
5. Predict and display the Iris species  

---

## 🚀 How to Run the Streamlit App

1. Install required libraries:
```bash
pip install pandas numpy scikit-learn streamlit
```

2. Run the application:
```
streamlit run app.py
```

## 📓 Jupyter Notebook (.ipynb)
The notebook contains:

Dataset exploration

Feature understanding

Model training

Prediction logic

Useful for learning and experimentation.

## 📈 Output Example

The app displays:
```
Prediction
The predicted species is: Setosa
```
