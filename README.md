# 📌 Visualizing CNN Filters using TensorFlow

This project demonstrates how to visualize the features learned by a Convolutional Neural Network (CNN) using TensorFlow. It generates images that maximize the activation of specific filters, helping to understand how CNNs interpret visual data.

---

## 🧠 Project Overview

CNNs learn hierarchical features from images, starting from simple edges to complex patterns. This project applies gradient ascent to create images that strongly activate specific filters of a pre-trained model.

---

## ⚙️ Methodology

- Load a pre-trained VGG16 model (trained on ImageNet)
- Create submodels to extract intermediate layer outputs
- Initialize a random image
- Apply gradient ascent to maximize filter activation
- Visualize the resulting patterns

---

## 🔍 Key Features

- Filter visualization using gradient optimization  
- Intermediate layer extraction (submodels)  
- Iterative training loop for feature maximization  
- Visualization of learned CNN representations  

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Jupyter Notebook / Google Colab  

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/visualizing-cnn-filters-tensorflow.git
```
2. Open the notebook:
```bash
jupyter notebook
```
3. Run all cells step by step

---
## 📊 Example Output

The model generates abstract patterns that represent what each filter detects (edges, textures, shapes, etc.).

---

## 🎯 Learning Outcomes

- Understanding how CNN filters learn features  
- Practical use of gradient ascent in deep learning  
- Insight into model interpretability  

---

## 📚 Acknowledgment

This project is based on a guided hands-on exercise from a Coursera deep learning project.

---

## 📌 Future Improvements

- Visualize deeper CNN layers  
- Apply the method to other architectures  
- Improve image clarity with regularization  
