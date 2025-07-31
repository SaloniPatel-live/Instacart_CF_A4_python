Instacart - Analysis

>> Instacart is an online grocery store that operates through an app. It currently has very good sales but they want to uncover more information about their sales patterns. 

>> The task is to perform an initital dta and exploratory analsysi fo some of their data in order to derive insights and suggest strategies dofr better segmentation based on the provided criteria. 

>> Some key questions covered in this analysis are - 
1. The sales team needs to know what the busiest days of the week and hours of the day are.
2. Create price ranges, regions, loyalty flags and spending habit flags.
3. Profile customers based on their shopping habits and income, age and family setup.
4. Create regions and understand if the shopping patterns are reflective of the location.
5. Are certain types of product more popular than others? What does the shopping cart tell us about a particular shopper?

>> Our main stakeholders are - 
1. Vice Presidents of Marketing - looking to improve target marketing strategies and make most of the advertising spending. 
2. Senior vice President of Sales - wants to know the company offerings that has the lowest market share and why so they can address the issue. 
3. Instacart Customer - focusing on ads, promotions and recommendations that are relevant to the purchase history.

>> The data provided is too large to share on github even after compressing. The data is available on - Departments, Orders - Products - Customers. 

>> Department Data has - 
1. department_id
2. department (department name)

>> Orders Data has -
1. order_id
2. user_id
3. eval_set
4. order_number
5. order_dow
6. order_hour_of_day
7. days_since_prior_order

>> Product Data contains - 
1. product_id
2. product_name
3. aisle_id
4. department_id
5. prices

>> Customer information is made up of - 
1. user_id
2. First Name
3. Surnam
4. Gender
5. STATE
6. Age
7. date_joined
8. n_dependants
9. fam_status
10. income
