# Day 1 - First ML Model (Chapter 1: Introduction)

## 📖 Topics Covered:
- Introduction to **Machine Learning** and its real-world applications.
- Types of machine learning:
  - **Supervised Learning** (with labels).
  - **Unsupervised Learning** (without labels).
- Understanding the **Iris dataset**.
- Building the first **classification model** using **k-Nearest Neighbors (k-NN)**.

## 🧠 Key Learnings:
- **Machine Learning Definition**: Teaching computers to learn patterns from data instead of hard-coded rules.
- **Supervised Learning** focuses on learning from labeled data (input → output), as done in this chapter.
- **Data Representation**: 
  - Samples = Rows
  - Features = Columns
- The **train-test split** is essential for model evaluation:
  - 75% training data, 25% testing data (default split in scikit-learn).
- Built a **k-NN Classifier**:
  - k-NN predicts the class of a data point based on the majority class of its nearest neighbors.
  - Evaluated using **accuracy** on the test set (achieved **97% accuracy** 🎯).

## 🚀 Reflections:
- The Iris dataset is a perfect beginner-friendly dataset – small, clean, and balanced.
- The **k-NN algorithm** is intuitive but might struggle with large datasets or many irrelevant features.
- Learned the importance of **model evaluation** on unseen data to avoid overfitting.

## 🔗 Related Files:
- **Notebook**: [IrisClassfierKnnModel.ipynb](../JupyterNotebooks/IrisClassfierKnnModel.ipynb)