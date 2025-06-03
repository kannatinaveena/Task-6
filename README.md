# K-Nearest Neighbors (KNN) Classification

This repository contains the implementation and evaluation of the K-Nearest Neighbors (KNN) algorithm on a classification dataset. The goal is to understand KNN, experiment with different values of K, and visualize decision boundaries.

---

## 📂 Dataset

- Used the **Iris Dataset** from `sklearn.datasets`
- Features normalized using `StandardScaler`

---

## 📌 Objectives

- Load and normalize dataset features  
- Split data into training and testing sets  
- Train KNN classifiers with various K values  
- Evaluate models using accuracy, confusion matrix, and classification report  
- Visualize decision boundaries using the first two features  

---

## 🛠️ Tools & Libraries Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🧾 Steps Performed

1. **Chosen Dataset and Normalized Features**  
   - Used the Iris dataset from `sklearn.datasets`  
   - Standardized features using `StandardScaler` for normalization

2. **Used KNeighborsClassifier**  
   - Imported and initialized `KNeighborsClassifier` from `sklearn.neighbors`  
   - Trained the model on the training data

3. **Experimented with Different Values of K**  
   - Tested multiple K values (1, 3, 5, 7, 9)  
   - For each K, trained a separate model and made predictions on the test set

4. **Evaluated Model Performance**  
   - Calculated accuracy scores for each K  
   - Generated confusion matrices and classification reports for detailed evaluation

5. **Visualized Decision Boundaries**  
   - Used the first two features to plot decision regions  
   - Created mesh grid and visualized classification zones with true test points overlaid

---

## 📊 Results

- Accuracy scores and confusion matrices for multiple K values printed in the console  
- Decision boundary plot showing classification regions for K=5  
- Accuracy vs K plot to illustrate model performance variation  

---
 
