# Marketing-Strategy
 Customer Data Analytics (Using marketing data)

(I used a data file in 'https://www.kaggle.com/datasets/jackdaoud/marketing-data')

Growth Hacking: Marketing Campaign Analysis based on Customer Data
This project explores a dataset from a virtual food retail company (ifood_df.csv) to analyze customer purchasing patterns and derive actionable insights for optimizing marketing campaign efficiency. By applying Growth Hacking principles, this analysis identifies high-value customer segments and factors that drive conversions.

Dataset Overview
- Source: ifood_df.csv
- Size: 2,205 rows × 39 columns
- Key Variables: Income, Household composition (Kidhome, Teenhome), Recency, Total Spending (MntTotal), Purchase Channels (Web, Store), and Campaign Response.

Key Insights & Analysis Results
1. Campaign Response Rate
- The overall conversion rate for the marketing campaign was approximately 15.1%.
- Out of 2,205 customers, 333 responded positively, while 1,872 did not.

2. Targeting Strategy by Income Level
- Customers were segmented into four income groups: low, mid-low, mid-high, and high.
- The 'high' income group showed a 27.0% response rate, significantly higher than the other groups (which averaged 10-12%).
- Insight: Focusing marketing efforts on high-income segments can drastically improve ROI.

3. Age Groups & Channel Preference
- Customers in their 20s and those over 50 showed higher average spending compared to those in their 30s and 40s.
- Older age groups tended to use both Web and Store purchase channels more frequently.

4. Impact of Household Composition
- Customers with no children at home spent an average of 1,041.2, while those with children spent only 372.2.
- Insight: Households without children are the "Heavy Users" and primary revenue drivers for this business.

5. Web Engagement vs. Purchase
- The analysis visualized the correlation between monthly website visits and actual web purchases to identify the "sweet spot" for digital engagement.

Tech Stack
- Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Tool: Jupyter Notebook / Google Colab

Conclusion & Recommendations
The data proves that "High-income customers without children" are the most valuable segment in terms of both campaign response and total revenue contribution.

Strategic Recommendation:
1. Allocate a larger portion of the marketing budget toward personalized messaging for high-income segments.
2. Develop premium product bundles specifically targeting childless households.
3. Optimize the web experience for older demographics who show high engagement across multiple channels.

How to Run
1. Clone this repository.
2. Ensure you have the ifood_df.csv file in the same directory.
3. Run the Growth_Hacking.ipynb notebook using Jupyter or Google Colab.
