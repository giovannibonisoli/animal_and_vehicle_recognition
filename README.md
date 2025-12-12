# Animal and Vehicle Recognition for Autonomous Vehicles

This project develops a deep-learning image classification system designed to help autonomous vehicles recognize the presence of animals and vehicles. Using a Convolutional Neural Network (CNN), the model is trained to distinguish between **animals** and **vehicles**, supporting safer decision-making in self-driving systems.

## 🚀 Project Overview

Autonomous driving systems rely heavily on accurate visual recognition to detect obstacles and living beings. This notebook explores a complete workflow—from data preparation to model evaluation—to build a reliable classifier using deep learning techniques.

## 📂 Features

* **Dataset loading & preprocessing**
  The dataset is cleaned, resized, normalized, and split into training and testing sets.

* **CNN model development**
  Implementation of a custom convolutional neural network built with standard deep-learning libraries.

* **Training and validation**
  Use of callbacks, augmentation, and regularization to reduce overfitting and improve performance.

* **Performance evaluation**
  Accuracy curves, loss curves, and detailed model predictions are analyzed.

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* scikit-learn

## 📁 Repository Contents

* `project.ipynb` – Main Jupyter Notebook containing the full project workflow
* (Optional) Add folders such as `data/`, `models/`, or `scripts/` if you include them later

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```bash
   jupyter notebook project.ipynb
   ```

## 📊 Results
---
The final model achieves solid performance in distinguishing vehicles from animals, demonstrating its usefulness as a building block for autonomous vehicle perception systems.

