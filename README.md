# Solar-Flare-Activity-Classification

## 📌 About the Project
This project focuses on classifying solar flare activity using machine learning algorithms and the **UCI Solar Flare Dataset**.

The dataset is used to categorize solar activity into three classes:
- **No Flare:** No recorded C, M, or X-class flares.
- **Low Activity:** C-class flares are recorded, with no M- or X-class flares.
- **High Activity:** At least one M-class or X-class flare is recorded.

## 🤖 Machine Learning Algorithms
Three classification algorithms are implemented and compared:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## ⚙️ Workflow
1. Dataset collection and loading
2. Data exploration and preprocessing
3. Target class creation
4. Stratified train-test splitting
5. Feature encoding and scaling
6. Model training and evaluation
7. Performance comparison and visualization

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Classification Reports
- Confusion Matrices

## 🏆 Results
- **Random Forest:** Highest accuracy of 70.86% and weighted F1-score of 71.84%.
- **SVM:** Highest macro F1-score of 41.69% and macro recall of 47.74%.

## 🛠️ Technologies Used
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Dataset
UCI Machine Learning Repository – Solar Flare Dataset

https://archive.ics.uci.edu/dataset/89/solar+flare

## 🎯 Objective
To apply supervised machine learning classification techniques to solar flare observations, compare model performance, and understand the challenges of classification with imbalanced datasets.

## ⚠️ Limitations
The dataset contains an imbalanced distribution of activity classes, making accurate identification of minority classes challenging.
