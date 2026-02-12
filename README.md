# Ecommerce Sales Analytics

## Overview
This is a Python project of mine created with the goal of analyzing sales trends for an e-commerce business and visualizing them. The project consisted of cleaning raw data, merging 3 data sources (Orders, Product info and Country info) into a single dataframe and analyzing sales trends by product type, region and sales channel. Throughout the code you can find business recommendations for this e-commerce business based on the data discovered, all of the comments in the code are made in Ukrainian.

## Tech Stack
- **Python** (Google Colab) for writing the code
- **Numpy** and **Pandas** libraries for data cleanup and analytics
- **Matplotlib** and **Seaborn** for visualizations

## Conclusions based on the data

### Key Company Performance Indicators
- Orders: 1,248
- Countries served: 45
- Revenue: $1.6B
- Costs: $1.1B
- Profit: $474M

### Key Insights
#### Product Categories

- Office Supplies generates the highest sales but also the highest costs
- Cosmetics is the most profitable category
- Office Supplies, Cosmetics, and Household are the strongest overall performers
- Meat shows high sales but low margins due to high costs
- Fruits has significant sales volume but extremely low profitability, requiring margin optimization

#### Sales Channels
- Sales are well balanced between online and offline channels, with slightly higher offline performance

#### Operations
- Order processing time does not strongly impact profitability but remains excessively high, especially in Eastern Europe

#### Sales Trends
- Strongest sales peaks occur in Office Supplies, Household, and Cosmetics
- Sales performance varies significantly across countries, with Portugal showing unusually high peaks
- Positive growth trends are visible in Serbia, Slovenia, and North Macedonia
- Sales in Asia are growing but remain less profitable

#### Weekly Patterns
- Cosmetics sales peak on Fridays
- Office Supplies sales drop on Saturdays
- Household sales drop on Tuesdays

### Recommendations
- Improve profitability of the Fruits category through pricing, supplier optimization, or product portfolio adjustments
- Optimize logistics to reduce order processing times, particularly in Eastern Europe
- Continue expansion into high-growth markets, especially Asia and selected Eastern European countries
