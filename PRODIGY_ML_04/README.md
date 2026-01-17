# ✋ Task 4: Hand Gesture Recognition (CNN)

**Prodigy Infotech Internship - Machine Learning Track**

### 📌 Project Overview
This project implements a **Convolutional Neural Network (CNN)** to identify and classify hand gestures from images. 

While the original task description mentions the *LeapGestRecog* dataset, this implementation uses the **Rock-Paper-Scissors** dataset from TensorFlow. This dataset serves as a standard, lightweight alternative that allows for efficient training of deep learning models in cloud environments like Google Colab without the overhead of processing 2GB+ of raw data.

### 📊 Model Output
The model was trained for 10 epochs. The graphs below show the training progress, achieving high accuracy on both training and validation sets.

<img width="1919" height="605" alt="Gesture_accuracy_1" src="https://github.com/user-attachments/assets/301a3f98-656a-4f78-8e64-3b79d3630338" />
<img width="1128" height="720" alt="Gesture_Accuracy2" src="https://github.com/user-attachments/assets/bdb7d3b2-7f4d-42e4-aa1c-75fe80086d3c" />


### 🛠 Technologies Used
* **Python**
* **TensorFlow & Keras** (Deep Learning Framework)
* **OpenCV / SciKit-Image** (Image Processing)
* **Matplotlib** (Visualization)

### 📂 Dataset
* **Source:** [Rock-Paper-Scissors Dataset (TensorFlow)](https://www.tensorflow.org/datasets/catalog/rock_paper_scissors)
* **Structure:** The dataset contains synthetic images of hands in different poses, rendered with various lighting conditions to simulate real-world diversity.

### 🚀 How to Run
1.  Open `PRODIGY_ML_04.ipynb` in Google Colab.
2.  Run the notebook cells. The script will automatically download the dataset and train the CNN model.
3.  Scroll to the bottom to see a test prediction on a sample image.
