#  Lab 8 – KNN Classification (Weight-Height Dataset)

This lab implements the **K-Nearest Neighbors (KNN)** algorithm to predict a person’s **Gender** using their **Height** and **Weight**.

---

##  Dataset
**File:** `weight-height.csv`  
**Columns:**  
- Gender (Male/Female)  
- Height (in inches)  
- Weight (in pounds)

---

##  Steps
1. Import libraries and load the dataset  
2. Explore and visualize data  
3. Encode the Gender column  
4. Split data into training and testing sets  
5. Train a **KNN model**  
6. Evaluate using accuracy, confusion matrix, and classification report  
7. Tune the **k** value for better accuracy  

---

##  Result
- Best Accuracy: ~91% (for k = 5)  
- KNN successfully classifies gender based on height and weight  

---

##  Requirements
```bash
pip install pandas numpy matplotlib scikit-learn
