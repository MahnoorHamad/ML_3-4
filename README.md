# Machine Learning Lessons – Decision Trees & Overfitting

This repository contains beginner-friendly **Machine Learning** lessons with both **theory** and **practical Python code**.  
Each lesson explains key ML concepts and provides runnable examples to help you learn step by step.

---

## 📘 Lesson 3 – Decision Trees
Decision Trees are a **supervised learning algorithm** used for both **classification** and **regression** tasks.  
They work by **splitting the dataset** into branches based on decision rules until reaching a prediction.

### Key Topics
- **How Decision Trees Work** – Build a model by recursively splitting data based on features.
- **Types of Trees** – Categorical Variable Tree (classification) & Continuous Variable Tree (regression).
- **Important Terms** – Root Node, Decision Node, Leaf Node, Pruning, Information Gain, Gini Impurity.
- **Example** – Training a Decision Tree classifier on the Iris dataset.

👉 *Run the code:* [lesson_3/decision_tree.py](lesson_3/decision_tree.py)  
This script trains a Decision Tree on the Iris dataset and prints the model accuracy.

---

## 📗 Lesson 4 – Overfitting & Model Evaluation
**Overfitting** occurs when a model learns the noise and details of the training data so well that it fails to generalize to new, unseen data.

### Key Topics
- **Learning Curves** – Compare performance on training vs. testing sets to detect overfitting.
- **Good Fit Concept** – Find the sweet spot where the model performs well on both train & test data.
- **Prevention Techniques**  
  - Reduce model complexity (fewer layers/nodes).  
  - Apply **Cross-Validation** for better evaluation.  
  - Use **Regularization** (L1/L2 penalties).  
  - Apply **Dropout** or **Data Augmentation** for deep learning models.

👉 *Run the code:* [lesson_4/overfitting_analysis.py](lesson_4/overfitting_analysis.py)  
This script demonstrates a learning curve using a neural network to visualize overfitting.

---

## 🛠️ How to Run online
https://colab.research.google.com

---
