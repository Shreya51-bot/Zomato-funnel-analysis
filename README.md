Zomato Funnel & Retention Analysis

Product Analytics | Funnel Analysis | Retention Analysis | Python | Pandas | Data Visualization
 
________________________________________
Project Overview

This project focuses on understanding how users move through a typical food delivery app journey similar to Zomato. The goal was to analyze user behavior and identify where users drop off before completing an order.

Since real product data from Zomato is not publicly available, I created a simulated dataset representing around 5000 users interacting with the platform. Using this dataset, I performed funnel analysis and retention analysis to understand how users progress through the ordering process.

The project helped me practice product analytics concepts such as conversion metrics, user drop-off analysis, and retention tracking.
________________________________________

Key Takeaways

• Around 80% of users browse restaurants after opening the app
• Only ~60% of users add items to the cart
• Final order conversion rate is roughly ~12%
• The largest drop in the funnel happens at
Restaurant View → Add to Cart
This stage appears to be the biggest opportunity to improve conversions.
________________________________________

Objective

The main objective of this project was to analyze the ordering journey of users in a food delivery application.
The funnel stages analyzed were:
App Open → Restaurant View → Add to Cart → Checkout → Order Complete
By studying this funnel, it becomes easier to identify friction points in the product and think about possible ways to improve user conversion.
________________________________________

Tools & Technologies

The following tools were used in this project:
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Google Colab
•	Git & GitHub
Python was mainly used for data simulation and analysis, while visualization libraries helped in presenting insights clearly.
________________________________________

Dataset

Because real Zomato user data is not publicly accessible, I generated a simulated dataset with 5000 users.
The dataset tracks whether a user completed each stage of the ordering journey:
•	app_open
•	restaurant_view
•	add_to_cart
•	checkout
•	order_complete
Each column represents whether the user progressed through that stage.
________________________________________

Funnel Analysis

Funnel analysis helps understand how many users move from one stage to the next in the ordering process.
Stage	Users	Conversion Rate
App Open	5000	100%
Restaurant View	~4000	~80%
Add to Cart	~3000	~60%
Checkout	~1500	~30%
Order Complete	~600	~12%
From this funnel, we can see that although many users explore restaurants, only a small portion eventually complete the order.
________________________________________

Key Product Metrics

Conversion Rate (App Open → Order Complete): ~12%
Largest Drop-Off Stage:
Restaurant View → Add to Cart
Estimated Drop-Off:
Around 40% of users leave before adding items to their cart
Retention Insights:
Day 1 Retention: ~60%
Day 7 Retention: ~40%
Day 30 Retention: ~25%
________________________________________

Funnel Visualization
 
The visualization above clearly shows how the number of users decreases at each stage of the ordering journey.
________________________________________

Key Insight

The most noticeable drop in the funnel occurs between:
Restaurant View → Add to Cart
This suggests that users are comfortable browsing restaurants, but many hesitate when it comes to actually selecting food items.
Possible reasons for this behavior could include:
•	Users comparing multiple restaurants before deciding
•	Menu prices appearing too expensive
•	Delivery charges discouraging orders
•	Lack of clear recommendations or popular dishes
•	Limited food images or menu details
________________________________________

Retention Analysis

Retention analysis was also performed to understand how many users return to the platform over time.
Day	Retention
Day 0	100%
Day 1	~60%
Day 7	~40%
Day 30	~25%
This type of analysis is commonly used in product teams to measure user engagement and long-term platform value.
Retention Curve
 
________________________________________

Product Recommendations

Based on the funnel and retention analysis, a few product improvements could potentially reduce drop-offs and improve order conversion:
•	Highlight most ordered dishes
•	Recommend budget-friendly meals
•	Display discounts and promotional offers clearly
•	Improve menu presentation with better food images
•	Add quick-add buttons for popular items
These changes could help users make decisions faster and encourage more users to complete the ordering process.
________________________________________

Project Structure

zomato-funnel-analysis
│
├── data
│   user_funnel_data.csv
│
├── notebooks
│   funnel_analysis.ipynb
│
├── visuals
│   funnel_chart.png
│   retention_curve.png
│
├── README.md
└── requirements.txt
________________________________________

How to Run This Project

1.	Clone the repository
git clone https://github.com/Shreya51-bot/Zomato-funnel-analysis.git
2.	Install the required dependencies
pip install -r requirements.txt
3.	Open the notebook
notebooks/funnel_analysis.ipynb
4.	Run the notebook cells to reproduce the analysis and visualizations.
________________________________________

Product Case Study

Problem
Many users open the food delivery app and browse restaurants, but only a small percentage actually complete an order.
The goal was to analyze the user journey and identify where the biggest drop-offs occur.
Approach
A simulated dataset representing 5000 users was created to model the food ordering journey:
App Open → Restaurant View → Add to Cart → Checkout → Order Complete
Using Python and Pandas, funnel metrics and retention rates were calculated to better understand user behavior.
Key Findings
•	About 80% of users view restaurants after opening the app
•	Only ~60% add items to their cart
•	Final order conversion is around ~12%
The largest drop-off happens between Restaurant View and Add to Cart.
Interpretation
This suggests that users are interested in exploring restaurants but hesitate before placing an order. Possible factors include pricing concerns, delivery fees, or difficulty choosing dishes.
Product Recommendations
To reduce drop-offs and improve conversions:
•	Highlight most ordered dishes
•	Recommend budget-friendly meal options
•	Display offers and discounts more prominently
•	Improve menu design with better food images
•	Provide quick-add options for popular dishes
Business Impact
Even a 10–15% improvement in the Restaurant View → Add to Cart stage could significantly increase:
•	Total orders
•	Revenue per user
•	Overall platform engagement

