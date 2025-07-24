# Will the Customer Accept the Coupon?

** Assginment notebook: https://github.com/ojbskvasu/ML-Assignment1/blob/main/prompt.ipynb

# Problem Statement 
Analyze the provided coupon dataset to identify the key characteristics and behaviors that differentiate users who accept coupons from those who reject them. 
Utilize statistical analysis and data visualization techniques to uncover actionable insights and provide recommendations for optimizing coupon campaigns to increase acceptance rates.

# What is the Data?
The data is contained in the data/coupons.csv file.Each row in the dataset represents an instance where a coupon was offered to a user.
The columns contain various attributes related to the user, the context of the offer (time, location, weather), and details about the coupon itself. 
The target variable, 'Y', indicates whether the coupon was accepted (1) or rejected (0)

# what are the finidngs?
  - Data Preparation: handled missing values by dropping the 'car' column and filling in missing frequency data with 'never'. 
  - Overall Acceptance:  found that overall, about {{acceptance_proportion:.2f}} of the coupons were accepted. 
  - Bar Coupon Analysis:  Drivers who visit bars more frequently are significantly more likely to accept bar coupons. Specific demographic and situational factors, such as age (over 25) combined with bar             frequency, and the absence of kids as passengers along with certain occupations, are associated with higher bar coupon acceptance. Combinations of factors related to bar visitation habits, age,              passenger type, occupation, and even cheap restaurant visits and income, collectively influence the likelihood of accepting bar coupons. 
       Coffee House Coupon Analysis: The overall acceptance rate for coffee house coupons is lower than the overall average. Younger drivers, those with friends or partners as passengers, individuals in            certain occupations (e.g., healthcare, cleaning), coupons offered at 10 AM, and particularly those who already frequent coffee houses are more likely to accept coffee house coupons. Temperature also         appears to have some relationship with coffee house coupon acceptance, with higher acceptance observed at certain temperatures.

# what do I recomended?
  - Focus on offering "Restaurant(<20)" coupons more frequently.
  - Target users with coupon offers around 10 AM and 6 PM
  - Consider weather and temperature when issuing coupons, favoring sunny days and moderate temperatures.
  - Offer coupons with longer expiration periods, such as 1-day, to potentially increase acceptance.
