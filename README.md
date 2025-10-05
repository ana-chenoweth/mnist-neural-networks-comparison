# Comparative Study of Regular and Convolutional Neural Networks on MNIST

This academic project explores the performance differences between a **Regular Neural Network (RNN)** — built using fully connected layers — and a **Convolutional Neural Network (CNN)** when classifying handwritten digits from the **MNIST dataset**.  

The goal is to understand how architectural choices affect model accuracy, generalization, and computational efficiency.

---

## Project Overview

Two models are trained on the MNIST dataset:

1. **Regular Neural Network**  
   - Composed of dense (fully connected) layers.  
   - Serves as a baseline for comparison.

2. **Convolutional Neural Network (CNN)**  
   - Uses convolutional and pooling layers to extract spatial features.  
   - Expected to outperform the regular model due to spatial pattern recognition.

Both models are trained, evaluated, and their performance metrics (accuracy, loss, training time) are compared.

---

## Results and Visualization

The models’ results are saved as a **JSON file** and visualized through a simple web page (`index.html`) that dynamically loads the data.  
This allows for an interactive comparison of the models’ metrics such as:

- Training and validation accuracy  
- Training and validation loss  
- Epoch duration and total training time  

---

## Technologies Used

- **Python**  
- **TensorFlow / Keras**  
- **NumPy**  
- **Matplotlib / Seaborn**  
- **HTML, CSS, JavaScript (for visualization)**

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AnaLauraChenoweth/mnist-neural-networks-comparison.git
   cd mnist-neural-networks-comparison
