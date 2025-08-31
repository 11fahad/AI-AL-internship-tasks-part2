# AI-AL-internship-tasks-part2
My completed tasks for DevelopersHub AI/ML Internship

---
**Author**: FAHAD TARIQ  
**Internship**: AI/ML Engineering Internship – DevelopersHub Corporation  
**Submission Date**: 31 Augest,2025

## 📌 Tasks Overview

### **Task 1 – News Topic Classifier**
- **Objective:** Classify short news headlines into categories (Business, Sports, Science, Politics).  
- **Approach:** Implemented a pure-Python Naive Bayes-style classifier using bag-of-words features.  
- **Key Result:** Achieved reasonable classification accuracy on small test set.  

---

### **Task 2 – Customer Churn Prediction**
- **Objective:** Predict which customers are likely to churn using the Telco dataset.  
- **Approach:**  
  - Preprocessed categorical & numerical features.  
  - Built scikit-learn pipelines with Logistic Regression & Random Forest.  
  - Tuned hyperparameters via GridSearchCV.  
- **Key Result:** Best model achieved a strong ROC-AUC score on test data.  

---

### **Task 3 – Housing Price Prediction**
- **Objective:** Predict housing prices based on tabular features.  
- **Approach:**  
  - Generated synthetic dataset (bedrooms, bathrooms, sqft, year built).  
  - Applied RandomForestRegressor with hyperparameter tuning.  
- **Key Result:** Low MAE and RMSE on test set, scatterplot shows good correlation.  

---

### **Task 4 – Context-Aware Chatbot**
- **Objective:** Build a simple chatbot with memory and context.  
- **Approach:**  
  - Rule-based retrieval from a small knowledge base.  
  - Stored conversation history for context.  
- **Key Result:** Bot responds to known topics and maintains conversation context.  

---

### **Task 5 – Auto-Tagging Support Tickets**
- **Objective:** Automatically assign tags (Billing, Technical, Account, etc.) to support tickets.  
- **Approach:** Keyword-based scoring system that outputs top-3 tags for each ticket.  
- **Key Result:** Correctly tags simple support tickets; extendable to ML/LLM models.  

---
## 📝 About the Author

FAHAD TARIQ

AI/ML Intern @ DevelopersHub Corporation  
Passionate about applying machine learning to solve real-world problems with practical and efficient solutions.



## 🚀 How to Run
1. Clone the repository:  
   ```bash## 📝 About the Author
   git clone https://github.com/<your-username>/ai-ml-internship-tasks_part2.git
   cd ai-ml-internship-tasks
