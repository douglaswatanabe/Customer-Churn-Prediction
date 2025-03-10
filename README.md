# [PROJECT: CUSTOMER CHURN PREDICTION](https://github.com/douglaswatanabe/Customer-Churn-Prediction/blob/main/Customer%20Churn%20Prediction.ipynb)

This project was developed following the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology, with the goal of creating a predictive model to help reduce customer churn in the telecommunications industry. The model leverages historical customer data and specific usage patterns to identify at-risk customers and provide actionable insights for retention strategies.

The CRISP-DM methodology organizes the analytical process into six structured phases: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment. This approach transforms raw data into valuable insights, enabling more accurate predictions and effective solutions to complex business challenges.

The project is presented systematically: it begins with a definition of the business problem, followed by the development of each methodological phase. Finally, the results and potential financial impacts are discussed, highlighting the operational improvements and competitive advantages enabled by the implemented model.

## Business Problem

Telecommunications companies operate in a highly competitive market where customer retention is critical to maintaining profitability. **Customer churn**—the phenomenon where customers switch to a different provider or cancels their subscription—is a significant challenge. Losing customers not only reduces revenue but also increases acquisition costs, as acquiring new customers is more expensive than retaining existing ones.

In this project, the business problem is to **reduce customer churn** by identifying customers who are likely to leave the company. By predicting churn, the company can take proactive measures to retain at-risk customers, such as offering personalized discounts, improving customer service, or tailoring marketing campaigns.

## Project Goals

The primary goals of this project are:

1. **Predict Customer Churn:** Develop a machine learning model that accurately predicts whether a customer will churn based on their usage patterns, demographics, and service interactions.

2. **Provide Actionable Insights:** Identify key factors that contribute to churn to help the company address root causes.

3. **Improve Customer Retention:** Enable the marketing and customer service teams to design targeted retention strategies for high-risk customers.

4. **Increase Profitability:** Reduce churn rates, thereby increasing customer lifetime value and overall profitability.


## Success Metrics

To measure the success of the project, **technical metrics** (for model performance) and **business metrics** (for organizational impact) will be defined.
  
1. **Technical Metrics:**  
   - **Accuracy:** The primary metric for the Kaggle competition is accuracy, with a target of **at least 85%** on the validation set.  
   - **Precision and Recall:** Given the high cost of missing a churn prediction (false negative), recall for the "churn" class is prioritized, with a target of **at least 80%**.  
   - **F1-Score:** To balance precision and recall, an F1-score of **at least 0.75** for the "churn" class is targeted.  
   - **ROC-AUC:** An ROC-AUC score of **at least 0.85** is aimed for to ensure the model effectively distinguishes between churn and non-churn customers.  

2. **Business Metrics:**  
   - **Churn Rate Reduction:** The goal is to reduce the churn rate by **at least 10%** within six months of model implementation.  
   - **Customer Retention Cost Savings:** Retaining customers is expected to achieve a **15% reduction in customer acquisition costs**.  
   - **Customer Lifetime Value (CLV):** Improved retention strategies aim to increase CLV by **at least 5%**.

## Business Value

By addressing customer churn, the company can:
- **Increase Revenue:** Retaining customers ensures a steady revenue stream.
- **Reduce Costs:** Lower churn rates reduce the need for expensive customer acquisition campaigns.
- **Enhance Customer Satisfaction:** Proactively addressing customer concerns can improve overall satisfaction and brand loyalty.
- **Gain Competitive Advantage:** A data-driven approach to customer retention can differentiate the company from competitors.

## Conclusion  

The customer churn prediction project addresses the critical business challenge of retaining customers in a highly competitive telecommunications market. By leveraging machine learning, the project delivers actionable insights and a robust predictive model that exceeds all predefined success metrics. Below are the key findings and potential outcomes:  

1. **High-Performance Model:**  
   The Random Forest model achieves an accuracy of **98.04%**, recall of **87.15%**, and an ROC-AUC score of **93.22%**, surpassing the technical targets. This performance ensures the model can effectively identify at-risk customers, enabling proactive retention efforts.  

2. **Actionable Insights:**  
   The analysis reveals critical churn drivers, including **pricing sensitivity**, **service quality issues**, and **dissatisfaction with international plans**. These insights empower the marketing and customer service teams to address root causes and design targeted retention strategies.  

3. **Financial Impact:**  
   With a recall of 87.15%, the model can identify **521 at-risk customers**. By retaining **60 of these customers**, the company can reduce its churn rate from **14.07% to 12.66%**, achieving a **10% reduction**. This effort is estimated to save **\$78,300 annually** in revenue and acquisition costs, with potential savings scaling significantly as retention efforts expand.  

4. **Operational Efficiency:**  
   The model streamlines decision-making processes, allowing teams to focus on high-impact retention strategies. This not only improves operational efficiency but also enhances customer satisfaction and loyalty.  

5. **Competitive Advantage:**  
   The data-driven approach to customer retention positions the company as a market leader, differentiating it from competitors and strengthening its brand reputation.  

In summary, this project demonstrates the transformative potential of predictive analytics in addressing customer churn. By combining high model performance with actionable insights, the company can better retain customers, protect revenue, and drive long-term profitability. The success of this initiative highlights the value of leveraging data science to solve complex business challenges and achieve strategic goals.  

## Notes on Model Validation  

- It is important to note that the results of this project are based on a controlled environment using historical data and simulations. Certain assumptions were made to estimate the financial and operational impacts. While the results demonstrate significant potential, the model has not yet been validated in real-world market conditions. For a definitive evaluation, it is essential to conduct practical tests and monitor the impacts over time, accounting for real-world variables such as market fluctuations, seasonality, and other external factors.

