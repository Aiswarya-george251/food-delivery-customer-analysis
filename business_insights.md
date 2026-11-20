# Food Delivery Customer Analysis – Business Insights

## 1. Project Overview

This project analyses food delivery order data using MySQL to understand customer acquisition, repeat ordering behaviour, retention, and promotional effectiveness.

The objective is to identify customer behaviour patterns and provide insights that could help improve customer retention.

## 2. Dataset Overview

- Total orders: 73
- Unique customers: 47
- Delivered orders: 72
- Cancelled orders: 1
- Analysis period: January–March 2025

*Note: This is an educational dataset used for SQL analysis.*

## 3. Order Status Analysis

- 72 orders were delivered.
- 1 order was cancelled.
- The cancellation rate was approximately 1.37%.

**Insight:** The dataset shows a high delivery completion rate, with very few cancelled orders.

## 4. Customer Ordering Behaviour

- Total customers: 47
- Repeat customers: 12
- One-time customers: 35
- Repeat customer rate: 25.53%

### Order Frequency

| Number of orders | Customers |
|---|---:|
| 1 | 35 |
| 2 | 4 |
| 3 | 6 |
| 6 | 2 |

**Insight:** Most customers placed only one order. This suggests an opportunity to improve repeat purchasing and customer retention.

## 5. Customer Acquisition Analysis

| Acquisition month | New customers |
|---|---:|
| January | 41 |
| February | 4 |
| March | 2 |

**Insight:** Customer acquisition was heavily concentrated in January, with considerably fewer new customers acquired in February and March.

## 6. Customer Retention Analysis

Among the 41 customers acquired in January:

- 2 returned in February (4.88%).
- 6 returned in March (14.63%).
- 6 unique customers returned at least once during February or March (14.63%).

**Insight:** Only a small proportion of January customers placed another order during the following two months. This highlights a potential customer retention challenge.

## 7. Promotion Effectiveness Analysis

| First-order promotion | Customers | Returning customers | Return rate |
|---|---:|---:|---:|
| No promo | 18 | 1 | 5.56% |
| FIRSTORDER | 11 | 2 | 18.18% |
| NEWUSER | 11 | 2 | 18.18% |
| Tasty50 | 1 | 1 | 100% |

**Insight:** Customers who used FIRSTORDER and NEWUSER had higher observed return rates than customers who did not use a promotion.

However, this does not prove that promotions caused higher retention. The Tasty50 result is inconclusive because it represents only one customer.

## 8. Business Recommendations

1. Explore strategies to encourage first-time customers to place repeat orders.
2. Investigate why customer acquisition declined after January.
3. Further evaluate promotional campaigns using a larger dataset.
4. Track customer retention over longer periods.
5. Collect additional information such as order value and delivery time for deeper business analysis.

## 9. Conclusion

The analysis shows that most customers placed only one order, while a relatively small proportion returned during the following months.

Promotional-code users showed higher observed return rates in this dataset, although further analysis with more data is needed to establish whether promotions influence customer retention.

MySQL was used to analyse customer behaviour, acquisition, repeat ordering, retention, and promotion effectiveness.
