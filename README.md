# Will the Customer Accept the Coupon?

## Assignment Notebook
[Click here to view the assignment notebook](https://github.com/ojbskvasu/ML-Assignment1/blob/main/prompt.ipynb)

## Problem Statement
Analyze the provided coupon dataset to identify the key characteristics and behaviors that differentiate users who accept coupons from those who reject them. Utilize statistical analysis and data visualization techniques to uncover actionable insights and provide recommendations for optimizing coupon campaigns to increase acceptance rates.

## Data Overview
- **File Location:** `data/coupons.csv`
- **Description:** Each row in the dataset represents an instance where a coupon was offered to a user.
- **Target Variable:** `Y` (1 = Accepted, 0 = Rejected)
- **Attributes:** Includes user demographics, offer context (time, location, weather), and coupon details.

## Key Findings
- **Data Preparation:** Missing values were handled by dropping the 'car' column and imputing missing frequency data with 'never'.
- **Overall Acceptance Rate:** Approximately XX% of the coupons were accepted.
- **Insights by Coupon Type:**
  - **Bar Coupons:** Drivers who visit bars frequently are more likely to accept bar coupons. Age (over 25) and other demographic/situational factors further increase acceptance.
  - **Coffee House Coupons:** Acceptance rates are lower, especially among younger drivers, those with friends/partners as passengers, and individuals with less frequent coffee house visits.

## Recommendations
- Focus on offering "Restaurant(<20)" coupons more frequently.
- Target users with coupon offers around 10 AM and 6 PM.
- Consider weather and temperature when issuing coupons, favoring sunny days and moderate temperatures.
- Offer coupons with longer expiration periods (e.g., 1-day) to potentially increase acceptance.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/ojbskvasu/ML-Assignment1.git
