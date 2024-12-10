# **Harry Potter: House Classification and Character Face Recognition**

## **Table of Contents**  
1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Techniques and Models](#techniques-and-models)  
4. [Results](#results)  
5. [Usage](#usage)  
6. [Requirements](#requirements)  
7. [Future Work](#future-work)  
8. [Contact](#contact)  

## **Project Overview**  
This project uses data science and machine learning to the Harry Potter universe. It features:
This project uses data science and machine learning analyze and classify characters from the Harry Potter series into one of the four Hogwarts
 houses: **Gryffindor**, **Hufflepuff**, **Ravenclaw**, or **Slytherin**. Additionally, it applies facial recognition techniques 
 to identify characters. 

## **Features**  
- **Multiclass Classification**: Assign characters to Gryffindor, Hufflepuff, Ravenclaw, or Slytherin.  
- **Facial Feature Extraction**: Identify characters from facial images using HOG and LBP techniques.  

## **Techniques and Models**  

### **House Classification**  
- Models:  
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Random Forest (best-performing model with ~69% accuracy)  
  - Gradient Boosting Classifier  
  - Decision Tree Classifier  
- Metrics:
  - F1-Score: 0.69 (using Random Forest)  
  - Analysis: Confusion matrix, ROC curves, PR curve  

### **Facial Recognition**  
- Methods:  
  - **Histogram of Oriented Gradients (HOG)**: Captures global facial structures, with 86% accuracy.  
  - **Local Binary Patterns (LBP)**: Focuses on local texture patterns, with 75% accuracy.  

## **Results**  

### House Classification:  
- F1_score by House:  
  - Gryffindor: 77%  
  - Slytherin: 81%  
  - Hufflepuff: 54%  
  - Ravenclaw: 52%  

### Facial Recognition:  
- HOG Accuracy: 86%  
- LBP Accuracy: 75%  

## **Usage**  

### **1. House Classification**  
#### Input:  
- A CSV file containing character traits.  

#### Steps:  
1. Open the Jupyter Notebook and navigate to the corresponding cell for house classification.  
2. Upload the CSV file with character data (e.g., `Characters.csv`).  
3. Run all the cells, and the predicted house for each character will be printed directly below the cell.  

---

### **2. Facial Recognition**  
#### Input:  
- A facial image in `.jpg` or `.png` format.  

#### Steps:  
1. Open the Jupyter Notebook and navigate to the corresponding cell for facial recognition.  
2. Upload the image of the character you want to identify.  
3. Run the cell, and the name of the recognized character and confidence score will appear below the cell.  

---

## **Requirements**  
- **Programming Language**: Python 3.10  
- **Libraries**:  
  - `scikit-learn`  
  - `numpy`  
  - `matplotlib`  
  - `opencv-python`  

## **Future Work**  
- Improve model performance and accuracy across all houses by expanding the dataset with additional character traits and features, especially for houses like Hufflepuff and Ravenclaw that currently have less representation. 
- Improve facial recognition accuracy by incorporating a larger and more diverse dataset of character images, including varying expressions, angles, and lighting conditions.

## **Contact**  

**Helena Boneu**  
- Email: helenaboneu@gmail.com  

**Nerea de la Torre**  
- Email: nereadelatorre2004@gmail.com  
