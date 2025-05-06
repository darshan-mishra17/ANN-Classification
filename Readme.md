# 🤖 ANN Classification

A beginner-friendly **Artificial Neural Network (ANN)** model built using Python and TensorFlow/Keras to classify data with high accuracy. This project is part of my deep learning journey, showcasing how an ANN can be trained for binary and multi-class classification problems.

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


---

## 🚀 Features

- ✅ Build and train a custom ANN model  
- 📊 Evaluate performance using metrics like accuracy, confusion matrix  
- 📈 Visualize loss & accuracy curves  
- 🔬 Supports both binary and multi-class classification  
- 💾 Clean and modular codebase  

---

## 📁 Project Structure
````
ANN-Classification/
├── dataset/ # (Optional) Dataset storage
├── models/ # Saved models
├── notebooks/ # Jupyter notebooks for experiments
├── outputs/ # Generated graphs & logs
├── utils/ # Helper functions
├── train.py # Script to train the model
├── evaluate.py # Script to evaluate the model
└── requirements.txt # Python dependencies
````


---

## 🧠 Model Architecture

The ANN is built with:

- Input Layer  
- Hidden Layers with ReLU activation  
- Output Layer (Softmax/Sigmoid based on task)  
- Optimizer: Adam  
- Loss: Binary/Categorical Crossentropy  

---

## 📷 Sample Visualizations

> Make sure to generate and save your loss/accuracy plot in `outputs/` directory with filename `loss_accuracy_plot.png`.

<p align="center">
  <img src="outputs/loss_accuracy_plot.png" width="600" alt="Loss vs Accuracy">
</p>

---

## ⚙️ Installation

```bash
git clone https://github.com/darshan-mishra17/ANN-Classification.git
cd ANN-Classification
pip install -r requirements.txt
```
▶️ Usage
Training the model:
```
python train.py
```
Evaluating the model:
```
python evaluate.py
```
#💡 Future Improvements
Add support for image datasets (like MNIST/CIFAR)

Implement dropout/regularization

Add hyperparameter tuning options
