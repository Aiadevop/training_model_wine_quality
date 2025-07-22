# 🍷 Wine Quality Classification

## 🚀 Overview
This project focuses on training a machine learning model to classify wine quality into **high** or **low** categories. The goal is to build an accurate, balanced, and robust classifier that helps distinguish wine quality effectively using advanced algorithms.

## 🗂️ Project Structure
The project is divided into several key stages:

1. **Data Analysis and Preprocessing**  
   - Cleaning and preparing the dataset.  
   - Reducing classes to balance the dataset and simplify classification (high vs. low quality).  
   - Addressing overfitting to ensure the model generalizes well.

2. **Model Selection**  
   - Quick evaluation of various models to shortlist the best candidates.

3. **Model Evaluation**  
   - Detailed study of the top three models based on performance metrics:  
     - **XGBoost**  
     - **Random Forest**  
     - **LightGBM**

4. **Hyperparameter Tuning**  
   - Hyperparameters are fine-tuned independently in three separate Colab notebooks for each shortlisted model.

5. **Final Model Selection**  
   - XGBoost is chosen as the final model due to its superior performance.  
   - The final Colab notebook summarizes and showcases the selected XGBoost model.

## 📊 Performance Summary

The final XGBoost model’s performance on the test set (with a custom threshold) is as follows:

| Class            | Precision | Recall | F1-Score | Support |
|------------------|-----------|--------|----------|---------|
| Low Quality (0)  |   0.819   | 0.819  |  0.819   |   149   |
| High Quality (1) |   0.842   | 0.842  |  0.842   |   171   |

**Overall metrics:**

- Accuracy: **83.1%**
- Macro Avg F1-Score: **0.830**
- Weighted Avg F1-Score: **0.831**
- ROC-AUC: **0.897**
  
## 🛠️ Technologies Used
- Python  
- Scikit-learn  
- XGBoost  
- LightGBM  
- Random Forest  
- Google Colab

## 📂 How to Use
1. Explore the notebooks starting with data cleaning and preprocessing.  
2. Review the model selection notebook to understand the initial evaluation.  
3. Check the hyperparameter tuning notebooks for detailed optimization steps.  
4. Finally, run the summary notebook with the chosen XGBoost model for predictions and performance analysis.

---

"The final Colab notebook loads the optimized XGBoost model, performs predictions, and displays a full evaluation including metrics and ROC curve."

*Made with ❤️ for wine lovers and data enthusiasts!*  
