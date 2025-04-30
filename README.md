# 🧠 Deep Learning Project: Multi-Class Image Classification

This project implements a deep learning-based image classification system using a custom dataset with multiple classes. The goal is to classify images into categories such as "applauding", "climbing", "holding_an_umbrella", etc., using a Convolutional Neural Network (CNN).

---

## 📌 Project Overview

- Performed stratified train-test split to ensure class representation
- Detected and addressed **class imbalance** across categories
- Built and trained a CNN using TensorFlow/Keras
- Evaluated model using metrics like **accuracy**, **precision**, **recall**, and **confusion matrix**

---

## 🧾 Dataset

The dataset contains labeled image data, where each image is associated with a specific human activity class.

**Examples of classes include:**
- `applauding`
- `climbing`
- `holding_an_umbrella`
- `cooking`
- `reading`
- and many more

---

## 🧰 Technologies Used

- Python 3
- NumPy, Pandas
- TensorFlow / Keras
- Matplotlib, Seaborn
- Scikit-learn

---

## 🛠 Workflow

1. **Data Preprocessing**
   - Loaded and analyzed image metadata
   - Performed class-balanced train/test split (80/20)
   - Exported training and test sets to CSV

2. **Model Building**
   - CNN architecture using Conv2D, MaxPooling, Dropout, and Dense layers
   - Applied appropriate activation functions and regularization

3. **Model Evaluation**
   - Accuracy score
   - Confusion matrix visualization
   - Handling of class imbalance through data augmentation or weighting

---

## 📈 Results

- Achieved solid classification performance on diverse activity classes
- Identified class imbalance as a challenge and mitigated it during training

*(Include specific accuracy/F1 scores once finalized)*

---

## 🚀 Getting Started

### Installation

```bash
pip install tensorflow pandas numpy matplotlib seaborn scikit-learn


📂 Project Structure

├── DEEP_LEARNING PROJECT.ipynb
├── train.csv
├── test.csv
├── /images/
└── README.md


👤 Author
Mohammed Tazwar Islam
Bachelor of Data Science
s3983534@student.emt.edu.au

📜 License
This project is open-sourced under the MIT License.

🙌 Acknowledgements
TensorFlow team

Keras documentation

Public image datasets and annotation tools
