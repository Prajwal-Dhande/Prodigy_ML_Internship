# 🐶 Task 3: Image Classification (SVM)

**Prodigy Infotech Internship - Machine Learning Track**

### 📌 Project Overview
This project implements a **Support Vector Machine (SVM)** to classify images of cats and dogs.

Unlike deep learning approaches (like CNNs), this task focuses on using a classic Machine Learning algorithm (SVM) to understand how it handles high-dimensional image data (raw pixel intensities).

### 📊 Model Output
The model was trained on a subset of the dataset (1000 images) to ensure feasibility within a standard execution environment.

<img width="1580" height="760" alt="Classisfication_Result" src="https://github.com/user-attachments/assets/eab2d58a-59be-4469-9d91-7369381f68b7" />


**Current Accuracy:** ~55-60%
* *Note: This accuracy is expected for a standard SVM trained on raw pixel data without complex feature extraction (like HOG) or Deep Learning (CNN).*

### 🛠 Technologies Used
* **Python**
* **Scikit-learn** (SVM Classifier)
* **Scikit-image** (Image Resizing & Processing)
* **Matplotlib** (Visualization)

### 📂 Dataset
* **Source:** [Kaggle - Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data)
* **Implementation:** Used a direct download of a dataset subset (`cats_and_dogs_filtered`) to streamline the training process in Google Colab.

### 🚀 How to Run
1.  Open `PRODIGY_ML_03.ipynb` in Google Colab.
2.  The notebook handles the dataset download automatically (no manual upload required).
3.  Run all cells to train the SVM and visualize the predictions.
