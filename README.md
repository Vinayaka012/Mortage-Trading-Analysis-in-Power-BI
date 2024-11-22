# Mortage-Trading-Analysis-in-Power-BI

Overview

In this project, I managed and analyzed mortgage data to facilitate high-stakes trades in the capital markets. Through a sequence of data transformations, financial calculations, and interactive reporting, the analysis provided a thorough look into mortgage trading—from bid analysis to profit assessment. This project enhanced my expertise in Power BI’s data modeling, DAX, Power Query, and AI-powered analytics.

Data Preparation and Transformation

I began by cleaning and preparing loan data to ensure accuracy and consistency. Error handling was crucial: I replaced missing or erroneous values across key columns and removed redundant fields, transforming variables like interest rates into consistent formats. I also computed critical financial ratios, such as:

Loan-to-Value Ratio (60.44%) to assess collateral value against loan size.
Debt-to-Income Ratio (31.70%) to gauge borrowers’ repayment ability.
Bid Analysis and Benchmarking

The bid analysis involved identifying the highest bid for each loan among multiple bidders, revealing a top bid price of 108.68. I then benchmarked these bids against market data for mortgage-backed securities (UMBS bonds), as UMBS trades offer a simpler, more reliable alternative to whole-loan sales. Benchmark testing highlighted that 27.33% of loans had bids above the UMBS prices, indicating viable candidates for direct trading.

I calculated the Trade Premium—the difference between trade amounts and principal balances—for loans surpassing the benchmark, resulting in a total premium of $15.14 million. This quantified the potential profit from executing trades on competitive terms.

Weighted Price and Profit Calculations

To ensure that larger loans were fairly represented in the average bid analysis, I used a weighted average price (WA Price), giving more weight to loans with higher principal balances. This approach provided a realistic view of the average trade price, accounting for principal size variations.

Subsequently, I calculated the Loan Profit Margin of 7.073% and benchmarked it against the target profit margin of 5.00%, demonstrating that the actual profit from trades surpassed expectations. This comparison underscored the effectiveness of our pricing strategy and profit potential.

AI-Driven Insights

To enhance understanding of factors influencing loan pricing, I utilized Power BI’s Key Influencers visual. This tool revealed that factors such as loan amount, loan-to-value ratio, median FICO score, and debt-to-income ratio significantly impact loan prices. By isolating influences that decrease price, I identified elements affecting trade competitiveness, informing strategic adjustments for future trades.

Visual Reporting and Presentation

For the final report, I created an interactive dashboard summarizing:

Trade Execution Details: Counterparty breakdown with loan counts, scheduled balances, weighted prices, trade amounts, and premiums.
Visual Analysis: Clustered column and 100% stacked bar charts to showcase counterparty contributions to trade amounts and premiums.
The final output presents a streamlined view for decision-makers, highlighting profitable trades and the overall performance of the loan portfolio.

Outcome

This project equipped me with a comprehensive understanding of mortgage trading workflows, from data preparation to final profit analysis. It sharpened my skills in data transformation, DAX calculations, and financial benchmarking while showcasing Power BI’s AI tools for impactful analysis. This experience has deepened my knowledge of the financial industry and strengthened my ability to drive data-driven insights and strategic decision-making through data visualization and analytics.
