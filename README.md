# Analytics Group Project: Credit Risk Analysis

You are provided with a dataset to analyze using the skills learned in the course.

When working on the project, you are encouraged to consider the different stages of the data life cycle and the importance of using the right tools to efficiently answer as many of the project questions as you can. Make sure that your answers are clearly supported by insigts derived from analysing the provided dataset.

Feel free to be creative in how you present your findings to answer each project question. At the very minimum, you are expected to create a dashboard in Tableau Public (https://public.tableau.com/en-us/s/) with at least 3 different visualizations to help answer some of the project questions.

## Dataset:
You are required to analyze a dataset containing credit applications and credit records provided by a bank. You will be required to provide various business insights about the bank's lending strategy.

application_record.csv

| Feature name        | Explanation                                     | Remarks                                                                        |
|---------------------|-------------------------------------------------|--------------------------------------------------------------------------------|
| ID                  | Client number                                   |                                                                                |
| CODE_GENDER         | Gender                                          |                                                                                |
| FLAG_OWN_CAR        | Is there a car                                  |                                                                                |
| FLAG_OWN_REALTY     | Is there a property                             |                                                                                |
| CNT_CHILDREN        | Number of children                              |                                                                                |
| AMT_INCOME_TOTAL    | Annual income                                   |                                                                                |
| NAME_INCOME_TYPE    | Income category                                 |                                                                                |
| NAME_EDUCATION_TYPE | Education level                                 |                                                                                |
| NAME_FAMILY_STATUS  | Marital status                                  |                                                                                |
| NAME_HOUSING_TYPE   | Way of living                                   |                                                                                |
| DAYS_BIRTH          | Birthday                                        | Count backwards from current day (0), -1 means yesterday                       |
| DAYS_EMPLOYED       | Start date of employment                        | Count backwards from current day(0). If positive, it means the person currently unemployed. |
| FLAG_MOBIL          | Is there a mobile phone                         |                                                                                |
| FLAG_WORK_PHONE     | Is there a work phone                            |                                                                                |
| FLAG_PHONE          | Is there a phone                                 |                                                                                |
| FLAG_EMAIL          | Is there an email                                |                                                                                |
| OCCUPATION_TYPE     | Occupation                                      |                                                                                |
| CNT_FAM_MEMBERS     | Family size                                     |                                                                                |


Data Source: Kaggle - https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction



# Project Questions:
1. Which attributes of the provided dataset are the strongest indicators of credit risk?
2. Are there some attributes that are highly correlated? What implications might your findings have to the bank's approach to lending?
3. What additional data would you recommend for the bank to collect in order to make better credit risk predictions? What challenges do you anticipate?
