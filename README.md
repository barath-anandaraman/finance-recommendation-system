# finance-recommendation-system
### Synopsis: 
Traditional financial advice often lacks the personalization needed to be impactful for diverse financial situations. By leveraging data science methodologies and machine learning, we can move beyond generic advice. Unsupervised learning, particularly clustering, provides a powerful mechanism to segment individuals into distinct financial profiles based on their behaviors (income, expenses, savings, and debt). These profiles then serve as the foundation for a recommendation system that provides tailored advice, empowering users with the tools to achieve their long-term financial security goals.

The analysis is based on a synthetic personal finance dataset, sourced from Kaggle. This dataset provides a rich, realistic representation of financial behaviors and demographic information for over 32,000 individuals. (https://www.kaggle.com/datasets/miadul/personal-finance-ml-dataset/data). It contains rich features like ‘monthly_income_usd',  'monthly_expenses_usd',  'savings_usd', 'loan_amount_usd',  'monthly_emi_usd',  'debt_to_income_ratio' related to finance and expense.

### Getting Started
To explore and run the analysis:

Clone the repository:
``` Bash
git clone https://github.com/barath-anandaraman/finance-recommendation-system.git
cd finance-recommendation-system
# Install Dependencies: It's recommended to use a virtual environment.


pip install -r requirements.txt
```
``` Bash

jupyter lab
# or
jupyter notebook
#From the Jupyter interface, you can then open and run the productivity-dynamics.ipynb files 
# to see the sentiment analysis in action.
