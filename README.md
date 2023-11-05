# Customer Churn Analysis for Ödeal 📊

This repository hosts the code for analyzing customer churn based on transaction data for Ödeal. The analysis provides valuable insights into customer retention and loss patterns over time.

![piechart](https://github.com/Odeal-Hackathon/ChurnAnalysis/assets/83168207/2e8eb3b7-2caf-4178-a347-30611d038dfa)


## What is Churn Analysis?

Churn analysis is the evaluation of customer attrition in a business. By tracking when customers discontinue their transactions or interactions, businesses can identify patterns and reasons behind the loss of clients.

## Why is Churn Analysis Crucial for Ödeal?

- **Customer Retention Insight**: By understanding the churn rate, Ödeal can measure how well it retains customers over time.
- **Identifying At-Risk Customers**: Early identification of customers who may churn allows Ödeal to take preemptive action to retain them.
- **Service Improvement**: Insights from churn patterns can guide Ödeal in refining their services to meet customer needs more effectively.
- **Targeted Marketing**: Analyzing churn helps in tailoring marketing efforts towards the right customer segments, enhancing ROI.
- **Revenue Growth**: Ultimately, reducing churn rates can lead to increased revenue and growth for Ödeal.

## Analysis Function

The function `analyze_customer_churn` takes transaction data and calculates churn based on a specified threshold of inactive days. By default, if a customer has no transactions for 90 days, they are considered to have churned.

### Parameters

- `df`: A pandas DataFrame containing the transaction data.
- `id_col`: The name of the customer ID column.
- `transaction_date_col`: The column containing the transaction dates.
- `transaction_id_col`: The column containing the transaction IDs.
- `churn_days_threshold`: The threshold in days to determine if a customer has churned.

### Returns

A DataFrame with churn analysis by customer, including churn status and average transaction frequency per month.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](https://www.apache.org/licenses/LICENSE-2.0) file for details.
