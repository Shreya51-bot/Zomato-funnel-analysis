\# Zomato Funnel \& Retention Analysis



\## Project Overview



This project analyzes the user journey in a food delivery application similar to Zomato.

The goal is to understand user behavior through funnel analysis and identify stages where users drop off before completing an order.



The analysis simulates a real product analytics workflow including:



\* User funnel analysis

\* Conversion rate calculation

\* Drop-off analysis

\* Retention analysis

\* Product insights and recommendations



\---



\## Objective



To analyze how users move through the ordering journey:



App Open → Restaurant View → Add to Cart → Checkout → Order Complete



By studying this funnel, we identify friction points and propose product improvements that could increase order conversions.



\---



\## Tools \& Technologies



\* Python

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* Google Colab

\* Git \& GitHub



\---



\## Dataset



Since real user behavior data from Zomato is not publicly available, a simulated dataset of \*\*5000 users\*\* was generated.



The dataset includes the following stages:



\* `app\_open`

\* `restaurant\_view`

\* `add\_to\_cart`

\* `checkout`

\* `order\_complete`



\---



\## Funnel Analysis



The user funnel tracks how users progress through each stage of ordering food.



| Stage           | Users | Conversion Rate |

| --------------- | ----- | --------------- |

| App Open        | 5000  | 100%            |

| Restaurant View | \~4000 | \~80%            |

| Add to Cart     | \~3000 | \~60%            |

| Checkout        | \~1500 | \~30%            |

| Order Complete  | \~600  | \~12%            |


## Key Product Metrics

Conversion Rate (App Open → Order Complete): ~12%

Largest Drop-Off Stage:
Restaurant View → Add to Cart

Estimated Drop-Off:
~40% users leave before adding items to cart.

Retention Insights:
Day 1 Retention: ~60%
Day 7 Retention: ~40%
Day 30 Retention: ~25%

\### Funnel Visualization



!\[Funnel Chart](visuals/funnel\_chart.png)



\---



\## Key Insight



The largest drop-off occurs between:



\*\*Restaurant View → Add to Cart\*\*



This suggests that many users browse restaurants but do not proceed to ordering.



Possible reasons:



\* Users comparing multiple restaurants

\* High menu prices

\* Delivery fees discouraging orders

\* Lack of item recommendations

\* Poor menu presentation



\---



\## Retention Analysis



Retention analysis evaluates how many users return to the platform over time.



| Day    | Retention |

| ------ | --------- |

| Day 0  | 100%      |

| Day 1  | \~60%      |

| Day 7  | \~40%      |

| Day 30 | \~25%      |



\### Retention Curve



!\[Retention Curve](visuals/retention\_curve.png)



\---



\## Product Recommendations



Based on the analysis, the following improvements could reduce drop-offs and increase orders:



\* Highlight \*\*popular dishes\*\*

\* Show \*\*budget-friendly recommendations\*\*

\* Add \*\*discount and offer badges\*\*

\* Improve \*\*menu UI with images\*\*

\* Introduce \*\*quick-add buttons for frequently ordered items\*\*



\---



\## Project Structure



```

zomato-user-funnel-analysis

│

├── data

│   user\_funnel\_data.csv

│

├── notebooks

│   funnel\_analysis.ipynb

│

├── visuals

│   funnel\_chart.png

│   retention\_curve.png

│

├── README.md

└── requirements.txt

```



\---



\## Key Learning



This project demonstrates how product teams use data to:



\* understand user behavior

\* identify friction points in the product

\* make data-driven product decisions

## How to Run This Project

1. Clone the repository
git clone https://github.com/Shreya51-bot/Zomato-funnel-analysis.git

2. Install dependencies
pip install -r requirements.txt

3. Open the notebook
notebooks/funnel_analysis.ipynb

4. Run the cells to reproduce the analysis.



