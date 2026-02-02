**EDA Findings – Summary Texts**
1. Data Quality & Structure
:-The dataset consists of 170 sales transactions with 20 attributes covering customer details, product hierarchy, geographic information, and financial metrics. Data quality is high, with less than 1% missing values originating from a single incomplete record, which was safely removed. Overall, the dataset is well-structured and suitable for business analysis.

2. Sales & Profit Distribution
:-Sales and profit distributions are right-skewed, indicating that a small number of high-value transactions significantly influence overall performance. While most orders generate modest revenue, a few transactions contribute disproportionately to total sales. Profit analysis reveals the presence of extreme negative values, highlighting loss-making orders that warrant further investigation.

3. Outlier Analysis
:-Outliers were detected using the Interquartile Range (IQR) method. Instead of removing them outright, high-value sales and quantity outliers were capped to reduce statistical distortion, while profit outliers were retained as they represent genuine business scenarios. This approach preserves analytical integrity while maintaining business relevance.
