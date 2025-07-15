
# 🧠 Handwritten Digit Recognition with SVM

This project implements a **Support Vector Machine (SVM)** model to recognize handwritten digits from the `sklearn` digits dataset. The model is trained to classify 8x8 grayscale images of digits (0–9) and evaluated for accuracy.

---

## 📊 Dataset

The dataset used is the built-in `digits` dataset from **scikit-learn**, which includes:

- **Images**: 8x8 pixel grayscale images of handwritten digits  
- **Target Labels**: Actual digit values (0 through 9)  
- **Total Samples**: 1,797  
This is a **multi-class classification** problem.

---

## 🧰 Libraries Used

- Python 3.x  
- `numpy`  
- `matplotlib`  
- `scikit-learn` (`sklearn`)

---

## ⚙️ Project Steps

1. Load the digits dataset using `sklearn.datasets.load_digits()`
2. Visualize sample digits using `matplotlib`
3. Preprocess the data and reshape input features
4. Split the dataset into training and testing sets
5. Train the SVM model using `SVC(kernel='linear')`
6. Predict outcomes for the test set
7. Visualize a single prediction from the test set
8. Evaluate the model using **accuracy score**

---

## ✅ Model Accuracy

The model achieved an accuracy of **97.11%** on the test dataset using a **linear kernel SVM**.

## 📸 Screenshot

![Sample Output](<img width="502" height="550" alt="SVM" src="https://github.com/user-attachments/assets/8d297fed-ed2f-4b96-a4c9-17659f0b7ba1" />)


## 🚀 How to Run

1. Clone the repo or download files
2. Open the Jupyter notebook: `SVM.ipynb`
3. Run all cells step-by-step
