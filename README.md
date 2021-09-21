# imbalanced-classfication-bank-customer-churn-prediction
  This project is an example of handling imbalanced classification problem. 

  The goal of this particular task is to:  
1) develop algorithms to identify customers who are likely to churn in the future;  
  2) analyze top factors that influence user retention;  
  3) interpret results and give business suggestions accordingly.

- Main take away:
    - Handling imbalanced classfication problem by stratified sampling and **SMOTE**, which enhanced ~50% of model performance.
    - Select **recall** as the most suitable metrics for this specific project, achieving best recall of 69.74% by XGBoost
    - 5 Most important factors:   
        - **Age**: older customer are more likely to churn;  
        -  **NumOfProducts**: churn customer tend to use more products;  
        - **Gender**: female are more likely to churn;   
        - **Geography**: Customer from Germany are more likely to churn;  
        - **IsActiveMember**: Non active members are more likely to churn.  
    - Business Suggestions: See [Part 6 Conclusion - Main suggestions](bank_customer_churn_prediction.ipynb#part6-suggest) 
    
