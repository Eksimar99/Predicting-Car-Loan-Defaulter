# Predicting-Car-Loan-Defaulter
In the ever-evolving financial landscape, accurately predicting loan default is paramount for financial institutions. This project aims to develop a sophisticated predictive model capable of identifying borrowers at high risk of default, enabling lenders to make informed decisions and mitigate potential losses.

By harnessing the power of machine learning, we will analyse a comprehensive dataset encompassing a wide range of borrower attributes, financial history, and economic indicators. Through rigorous data preprocessing, exploratory data analysis, and feature engineering, we will uncover underlying patterns and correlations that significantly influence loan default.
The primary objective is to construct a robust predictive model that can assess the probability of default for individual loan applications. This model will serve as a valuable tool for credit risk assessment, empowering financial institutions to:
* Optimise Credit Decisions: Make well-informed decisions regarding loan approvals, loan amounts, and interest rates.
* Enhance Risk Management: Proactively identify and manage high-risk borrowers.
* Improve Portfolio Performance: Minimise loan losses and optimise portfolio returns.
The anticipated impact of this project is far-reaching. By accurately predicting loan defaults, financial institutions can strengthen their credit risk management practices, reduce operational costs, and ultimately enhance overall financial stability. Furthermore, this project contributes to a more transparent and responsible lending environment, benefiting both lenders and borrowers.

### 1. Current Practices in Mitigating Loan Default Risk:
Traditional methods for assessing loan default risk often rely on a combination of manual review, credit scoring models, and historical data analysis. While these methods have proven valuable, they may not fully capture the complexities of modern lending environments.
* **Manual Review:** Credit analysts manually assess loan applications, considering factors such as income, employment history, and creditworthiness. However, this process can be time-consuming, subjective, and prone to human error.
* **Credit Scoring Models:** Statistical models, such as FICO scores, are used to evaluate creditworthiness based on historical data. While effective, these models may not fully account for emerging risk factors and may not be as accurate in predicting default in specific scenarios.
* **Historical Data Analysis:** Analysing past loan performance can provide insights into future trends. However, historical data may not always accurately predict future behaviour, especially in rapidly changing economic conditions.

By leveraging advanced machine learning techniques, this project aims to surpass the limitations of traditional methods and provide more accurate and reliable predictions of loan default.

### 2. Background Research :
The financial landscape is characterised by the constant interplay between lenders and borrowers. While lending institutions aim to maximise profits, they also face the inherent risk of loan default. This risk, if not effectively managed, can lead to significant financial losses for lenders. To mitigate these risks, financial institutions have traditionally relied on a combination of credit scoring models, manual review processes, and historical data analysis. However, these methods have limitations in accurately predicting default behaviour, especially in complex and evolving economic conditions.

The increasing volume of loan applications and the sophistication of financial products have further heightened the need for robust and accurate prediction models. As a result, the development of advanced machine learning techniques has emerged as a promising solution to address the challenge of loan default prediction. By leveraging these techniques, financial institutions can gain valuable insights into borrower behaviour, identify early warning signs of potential default, and make more informed credit decisions.

This project aims to contribute to the advancement of loan default prediction by developing a predictive model capable of assessing the likelihood of default for individual loan applications. By analysing a comprehensive dataset encompassing a wide range of borrower attributes, financial history, and economic indicators, the model will uncover hidden patterns and correlations that significantly influence default behaviour.

Loan default, the failure of a borrower to repay a loan, is a significant challenge for financial institutions. It can lead to substantial financial losses and negatively impact an institution's stability. Traditionally, financial institutions have relied on credit scoring models and manual review processes to assess creditworthiness and mitigate the risk of default. However, these methods have limitations in capturing the nuances of individual borrower behaviour and predicting future trends.

In recent years, machine learning has emerged as a powerful tool for predicting loan default. By leveraging advanced algorithms, machine learning models can analyse large datasets, identify complex patterns, and make accurate predictions. Several studies have demonstrated the superior performance of machine learning models over traditional methods in predicting loan default.

### 3. Literature Past and Undergoing Research: 
#### Predicting Loan Default in Financial Lending
The prediction of loan default has been a significant focus in the field of finance and machine learning. Financial institutions have long sought effective methods to assess credit risk and minimise losses. In recent years, machine learning techniques have emerged as powerful tools for predicting loan default.

A substantial body of research has explored the application of machine learning algorithms to loan default prediction. These studies have demonstrated that machine learning models can outperform traditional statistical models in terms of accuracy and predictive power.

#### Key findings from the literature:
* **Machine Learning Algorithms:** A variety of machine learning algorithms, including logistic regression, decision trees, random forests, and gradient boosting, have been successfully applied to predict loan default. These algorithms can capture complex patterns and relationships within the data, leading to improved predictive performance.
* **Data Preparation and Feature Engineering:** Data quality and feature engineering are crucial for accurate model predictions. Cleaning and handling missing values, outlier detection, and feature engineering (e.g., creating new features like debt-to-income ratio) are essential steps in preparing the data for modelling.
* **Model Evaluation:** Various metrics can be used to evaluate the performance of a loan default prediction model, including accuracy, precision, recall, F1-score, and ROC curve. The choice of metric depends on the specific business objectives and the cost of false positives and false negatives.
* **Model Interpretability:** Understanding the factors that influence the model's predictions is important for building trust and making informed decisions. Techniques like feature importance analysis and SHAPE values can help interpret the model's decision-making process.
* **Dynamic Economic Conditions:** The performance of loan default prediction models can be affected by changes in economic conditions. It is important to periodically retrain and update models to account for evolving economic factors.

By leveraging machine learning, financial institutions can build more accurate and reliable models to assess creditworthiness and make informed lending decisions. This can help reduce loan defaults, improve risk management, and enhance overall financial performance.

## ABSTRACT OF PROJECT:
The project focuses on addressing the challenge of imbalanced class prediction in a machine learning model, particularly where the minority class ("1") is completely missed. To enhance recall for the minority class and improve overall model performance, fine-tuning techniques were explored. Key approaches included resampling techniques such as oversampling class "1" or undersampling class "0" to balance the class distribution, and adjusting class weights in the logistic regression model to prioritize recall for the minority class. Additionally, the study considered employing more complex models, such as decision trees, random forests, and boosting algorithms, to better capture patterns of the minority class. Threshold tuning was also investigated to increase model sensitivity for class "1." These methods collectively aim to mitigate the impact of class imbalance, ensuring a more robust and equitable predictive performance.
