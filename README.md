# Analytics Group Project: Credit Risk Analysis

You are provided with a dataset to analyze using the skills learned in the course.

When working on the project, you are encouraged to consider the different stages of the data life cycle and the importance of using the right tools to efficiently answer as many of the project questions as you can. Make sure that your answers are clearly supported by insigts derived from analysing the provided dataset.

Feel free to be creative in how you present your findings to answer each project question. At the very minimum, you are expected to create a dashboard in Tableau Public (https://public.tableau.com/en-us/s/) with at least 3 different visualizations to help answer some of the project questions.

## Dataset:
You are required to analyze a dataset containing credit applications and credit records provided by a bank. You will be required to provide various business insights about the bank's lending strategy.

#### application_record.csv

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

#### credit_record.csv

| Feature name    | Explanation            | Remarks                                                                                |
|-----------------|------------------------|----------------------------------------------------------------------------------------|
| ID              | Client number          |                                                                                        |
| MONTHS_BALANCE  | Record month           | The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on |
| STATUS          | Status                 | 0: 1-29 days past due<br>1: 30-59 days past due<br>2: 60-89 days overdue<br>3: 90-119 days overdue<br>4: 120-149 days overdue<br>5: Overdue or bad debts, write-offs for more than 150 days<br>C: paid off that month<br>X: No loan for the month |


Data Source: Kaggle - https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction



# Project Questions:
1. Based on the provided dataset, perform some descriptive analysis about the relationship between annual income and education level?
2. Are there some attributes that are highly correlated? What impact might this have on your analysis?
3. Are there some credit applicants that maybe considered as outliers? What makes them outliers?
4. Which attributes of the provided dataset are the strongest indicators of credit risk?
5. What implications might your findings have to the bank's approach to lending?
6. What additional data would you recommend for the bank to collect in order to make better credit risk predictions? What challenges do you anticipate?
