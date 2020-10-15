# Credit scoring

The idea is to build a classification model based on client's info which predicts the probability that a certain client will default (i.e. will not be able to repay a loan)

**The dataset contains the following information on clients:**

1. client_id - client's id number
2. education - level of education
3. sex - client's sex
4. age - client's age
5. car - car presence
6. car_type - foreign car or not
7. decline_app_cnt - number of previous credit refusals
8. good_work - "good" job presence
9. bki_request_cnt - number of loan requests to Credit Bureau
10. home_address - category of home address
11. work_address - category of work address
12. income - client's income
13. foreign_passport - foreign passport presence
14. default - default presence (i.e. failure to fulfil an obligation/to repay a loan)
15. app_date - application date
16. first_time - how long the bank has info about this client
17. sna - relation to bank's clients (i.e. if a client has friends/relatives who are also clients of this bank)
18. region_rating - client's region rating

Target metrics is **AUC**



**Kaggle competition:** https://www.kaggle.com/c/sf-dst-scoring
