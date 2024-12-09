# **Harry Potter: House Classification and Character Face Recognition**

## **Project Overview**
This project uses data science to analyze and classify characters from the Harry Potter series into one of the four Hogwarts houses: **Gryffindor**, **Hufflepuff**, **Ravenclaw**, or **Slytherin**. Additionally, it applies facial recognition techniques to identify characters using facial images.

### Main Components:
1. **House Classification**:
   - Implemented models: LogisticRegression, SVM, Random Forest, Gradient Boosting Classifier and Decision Tree Classifier
   - Average accuracy using Random Forest: ~69%.
   - Analyses: F1-Score, confusion matrices, ROC curves and PR curve.

2. **Facial Recognition**:
   - Techniques used: **Histogram of Oriented Gradients (HOG)** and **Local Binary Patterns (LBP)**.
   - HOG outperformed LBP in capturing global facial features.

## **Features**
- **Multiclass classification**: Assign characters to one of the four Hogwarts houses.
- **Facial feature extraction**: Identify characters through facial analysis.

## **Usage**
1. **House Classification**:
   - Provide a CSV file with character features.
   - The model will assign each character to a house.

2. **Facial Recognition**:
   - Upload a facial image.
   - The script will identify the character based on HOG and LBP techniques.

## **Results**
### House Classification:
- **Accuracy by house**:
  - Gryffindor: 77%
  - Slytherin: 81%
  - Hufflepuff: 54%
  - Ravenclaw: 52%
  
- **Overall evaluation**:
  - F1-Score: 0.69

### Facial Recognition:
- HOG outperformed LBP in overall accuracy.
- **HOG**:
    - Accuracy: 0.86
- **LBP**:
    - Accuracy: 0.75

## **Contact**
Created by: [Helena Boneu]
Email: helenaboneu@gmail.com

Created by: [Nerea de la Torre]
Email: nereadelatorre2004@gmail.com
