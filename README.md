# Customer Segmentation Analysis – Online Retail Dataset

## Overview
This project explores customer segmentation using the UCI Online Retail dataset. The goal was to practice data cleaning, exploratory analysis, and customer segmentation techniques in Python using transaction-level retail data.

This project was completed as a hands-on learning exercise to strengthen practical data science skills.

## Dataset
- **Source:** UCI Machine Learning Repository
- **Dataset:** Online Retail Dataset
- **Description:** Transaction data from a UK-based online retailer between 2010–2011.

Dataset link: https://archive.ics.uci.edu/dataset/352/online+retail

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Project Process
The notebook includes the following steps:

1. Loading and exploring the retail transaction dataset  
2. Cleaning and preparing the data  
3. Creating customer-level features for analysis  
4. Applying customer segmentation techniques  
5. Exploring patterns in customer purchasing behavior
6. Create a customer segmentaion marketing playbook  

## Key Skills Practiced
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Customer Segmentation
- Feature Engineering
- Python for Data Analysis

## Marketing Playbook
Each segment below gets a specific strategy.

🏆 Champions
Who they are: Bought recently, buy often, spend the most.
Goal: Reward loyalty, activate as brand advocates.

Tactics:
Early access to new products / launches
VIP loyalty tier or exclusive rewards
Referral program — these customers will convert their network
Solicit reviews and UGC

⭐ Loyal / Regulars
Who they are: Recent, moderately frequent buyers with solid spend — not top-tier, but consistent.
Goal: Nurture toward Champions status; reward consistency without over-discounting.

Tactics:
- Frequency-building incentive: "buy again within 30 days" nudge rather than a broad discount — reward the behavior you want more of, not just the purchase
- Bundle or cross-sell recommendations based on first/most recent purchase category, aimed at raising AOV per visit
- Progress-based loyalty messaging ("you're 2 purchases away from VIP") if you have or plan a tier system — gives them a visible path to Champions
- Segment out of blanket win-back or reactivation email flows — they don't need to be won back, and treating them like a lapsed customer risks training them to expect discounts they don't need to be incentivized with

🌱 Promising / New
Who they are: Recent first-time or early buyers with growth potential.
Goal: Convert into repeat buyers fast — the first 90 days are critical.

Tactics:
- Onboarding email series focused on product education
- Second-purchase incentive (small discount or free shipping threshold)
- Cross-sell based on first purchase category
- Social proof: reviews, bestsellers in their category

💤 Hibernating
Who they are: Haven't bought in a long time, low frequency, low spend.
Goal: Either reactivate cheaply or suppress from paid campaigns to protect ROAS.

Tactics:
- One last aggressive win-back attempt (deep discount or bundle)
- If no response: move to suppression list for paid ads
- Low-cost email only — don't waste paid budget here
- Consider a sunset flow: unsubscribe the truly gone ones to protect deliverability

🔮 Layer on Predictive Modeling
A model that predicts each customer's future value based on their early buying behavior: 
— How often they buy, how long they've been a customer, and what they typically spend 
— rather than just looking at their purchase history so far. This would flag customers on track to become Champions before they've racked up enough purchases to show up as one in the RFM data, so VIP treatment can start early instead of waiting for the numbers to catch up.

## Notes
This project was completed for practice and learning purposes to strengthen applied data science skills.
