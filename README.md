# Handwritten Digit Prediction using Logistic Regression  

This project demonstrates multiclass classification using logistic regression to predict handwritten digits (0-9) based on pixel data. The dataset used is the inbuilt `load_digits` dataset from scikit-learn, which contains images of digits in an 8x8 pixel grid format.  

---

## Overview  
The dataset contains 1,797 grayscale images of digits (0-9), each represented as an 8x8 pixel array. The goal is to train a logistic regression model to classify these images into the corresponding digits.  

---

## Features  
- **Pixel Data:** 64 features representing pixel intensity values (8x8 grayscale images).  
- **Target Labels:** Digits (0-9) corresponding to the images.  

---

## Technologies Used  
- **Python**: Programming language.  
- **scikit-learn**: For data handling, model building, and evaluation.  
- **matplotlib**: For visualizing images and results.  

---

## How It Works  
1. **Data Loading and Preprocessing**:  
   - Load the `load_digits` dataset from scikit-learn.  
   - Visualize some sample images and their labels.  
   - Split the data into training and test sets.  

2. **Model Building**:  
   - Use scikit-learn's `LogisticRegression` class with multiclass classification support.  
   - Train the model using the training data.  

3. **Prediction and Evaluation**:  
   - Use the test data to predict digits.  
   - Evaluate the model using metrics such as accuracy and confusion matrix.  

---

## Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/username/handwritten-digit-prediction.git  
