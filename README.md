# customer-churn-prediction

Machine learning project to predict customer churn based on usage patterns, subscription details, and customer demographics using classification models.

## Dataset

- Filename: churn.csv  
- Description: This dataset contains customer data from a telecom service, including features like gender, internet service, contract type, tenure, and charges.  
- Target Variable: `Churn` (0 = No, 1 = Yes)

## Tools and Libraries

- Python  
- Jupyter Notebook  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  

## Project Structure

customer-churn-prediction  
- churn.csv  
- customer_churn_prediction.ipynb  
- README.md  
- requirements.txt  

## Models Compared

- Logistic Regression (Best)  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  
- Support Vector Machine  

## Evaluation Metric

- Accuracy Score  
- Confusion Matrix  
- Classification Report  

## Results

Logistic Regression gave the highest accuracy on the test set.

| Model                 | Accuracy |
|-----------------------|----------|
|**Logistic Regression**|**0.7825**|
| Random Forest         | 0.7818   |
| KNN                   | 0.7733   |
| SVM                   | 0.7342   |
| Decision Tree         | 0.7221   |

## Final Output

A classification report and confusion matrix were generated using the Logistic Regression model to evaluate prediction performance.

## How to Run

1. Clone this repository  
2. Ensure `churn.csv` is in the same folder as the notebook  
3. Open `customer_churn_prediction.ipynb` in Jupyter Notebook or Google Colab  
4. Run all cells in order  

## Author

Talasila Navya Annapurna  

GitHub: https://github.com/NavyaTalasila5  

LinkedIn: https://www.linkedin.com/in/navya-talasila-3134a1325/
