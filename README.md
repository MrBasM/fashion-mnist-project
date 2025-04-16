# 👗 Fashion MNIST Classifier

A simple deep learning project to classify clothing items using the Fashion MNIST dataset.  
Built as part of the **ZTM Complete A.I. Machine Learning & Data Science Bootcamp**.

## 🧠 What It Does

This project trains a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify grayscale images of clothing into 10 categories such as t-shirts, trousers, sneakers, etc.

## 📚 Dataset

- Fashion MNIST: 70,000 28x28 grayscale images of 10 fashion categories
- Provided by [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/fashion_mnist)

## 📓 Project Content

- `fashion_mnist.ipynb`: Jupyter notebook with training, evaluation, and visualization
- Model architecture: Simple CNN with Conv2D, MaxPooling, Dropout, and Dense layers
- Evaluation includes confusion matrix and accuracy plot

## 🛠️ Tools

- Python, TensorFlow/Keras
- Matplotlib, NumPy
- Google Colab

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run all cells to train and evaluate the model
3. No external data download required (dataset is loaded via `tf.keras.datasets`)

## 📈 Results

Achieved over **X% accuracy** on the test set. *(Replace with your result)*

## 📌 Improvements

- Add data augmentation
- Test with different optimizers and architectures
- Deploy as web app using Streamlit or Gradio

---

Made with ❤️ by [Mr. Bas](https://github.com/MrBasM)
