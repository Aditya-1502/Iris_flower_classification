# Iris_flower_classification
This project implements a Logistic Regression model to classify Iris flowers into three species — Setosa, Versicolor, and Virginica — based on their sepal and petal measurements.  Key Features:

Here’s a **complete `README.md`** for your Iris Logistic Regression project that you can directly use on GitHub:

---

# 🌸 Iris Flower Classification using Logistic Regression

This project demonstrates the implementation of a **Logistic Regression model** to classify Iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — using their **sepal length, sepal width, petal length, and petal width**.

The Iris dataset is a well-known dataset in machine learning and is often used for beginner classification problems.

---

## 📌 Project Overview

* **Goal**: Predict the species of an Iris flower based on its measurements.
* **Algorithm**: Logistic Regression (Multi-class classification).
* **Dataset**: Built-in Iris dataset from `scikit-learn`.
* **Performance Metric**: Accuracy Score, Confusion Matrix, Classification Report.

---

## 📊 Dataset Information

The Iris dataset contains:

* **150 samples**
* **4 features**:

  * Sepal length (cm)
  * Sepal width (cm)
  * Petal length (cm)
  * Petal width (cm)
* **3 classes**:

  * 0 → Iris-setosa
  * 1 → Iris-versicolor
  * 2 → Iris-virginica

---

## ⚙️ Technologies Used

* **Python 3**
* **Libraries**:

  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
  * Scikit-learn

---

## 📂 Project Structure

```
├── iris_logistic_regression.ipynb   # Jupyter notebook with code
├── README.md                        # Project description
└── requirements.txt                 # Python dependencies
```

---

## 🚀 Steps Performed

1. **Import Libraries** – Loaded necessary Python libraries.
2. **Load Dataset** – Used `load_iris()` from scikit-learn.
3. **Exploratory Data Analysis (EDA)** – Checked dataset structure, visualized distributions.
4. **Data Preprocessing** – Separated features (X) and target (y).
5. **Train-Test Split** – Split data into training and testing sets.
6. **Model Training** – Applied Logistic Regression from scikit-learn.
7. **Model Evaluation** – Measured accuracy and plotted confusion matrix.
8. **Visualization** – Plotted decision boundaries and class separation.

---

## 📈 Results

* Achieved high accuracy on the test set.
* The confusion matrix shows correct classification for most samples.
* Logistic Regression performed well on this dataset.

---

## 📸 Sample Output

*(Insert an image of your accuracy score or confusion matrix here if you have one)*

---

## 🛠 Installation & Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/iris-logistic-regression.git
   cd iris-logistic-regression
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook iris_logistic_regression.ipynb
   ```



## 📚 References

* [Scikit-learn Documentation](https://scikit-learn.org/stable/)
* [Iris Dataset - Wikipedia](https://en.wikipedia.org/wiki/Iris_flower_data_set)


