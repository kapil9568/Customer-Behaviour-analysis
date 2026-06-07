# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using transaction data from 3,900 purchases. The objective is to uncover customer trends, purchasing patterns, and business opportunities that can help improve marketing strategies, customer retention, and overall revenue.

The analysis includes customer demographics, purchasing habits, subscription impact, shipping preferences, product ratings, and customer segmentation.

---

## Dataset Information

- Total Records: 3,900 purchases
- Total Features: 18 columns
- Missing Values: 37 records in the Review Rating column
- Data Type: Customer transaction and shopping behavior data

---

## Project Objectives

- Analyze customer purchasing behavior
- Identify high-value customer segments
- Evaluate the impact of subscriptions on revenue
- Study shipping preferences and spending patterns
- Discover top-rated products
- Generate actionable business recommendations

---

## Technologies Used

- Python
- Pandas
- NumPy
- PostgreSQL
- Jupyter Notebook
- Data Visualization Libraries (Matplotlib / Seaborn)

---

## Data Preparation Process

1. Data Loading using Pandas
2. Initial Data Exploration
3. Missing Value Treatment
   - Review Rating missing values replaced using median imputation
4. Feature Engineering
   - Customer Age Groups
   - Purchase Frequency Categories
5. PostgreSQL Database Integration
6. Data Analysis and Visualization

---

## Key Insights

### Revenue by Gender
- Female customers generated slightly higher revenue compared to male customers.
- Gender-specific marketing campaigns can improve revenue generation.

### High-Value Discount Users
- Identified customers who spend above average while utilizing discounts.
- These customers represent an opportunity for premium promotional campaigns.

### Top-Rated Products
| Product | Rating |
|----------|----------|
| Blouse | 5.0 |
| Dress | 5.0 |
| Shirt | 4.0 |

### Shipping Preference Analysis
- Express Shipping Average Purchase: $65
- Standard Shipping Average Purchase: $58
- Customers choosing express shipping spend approximately 12% more per transaction.

### Subscription Impact
- Subscribers spend 68% more than non-subscribers.
- Subscription customers contribute 45% of total revenue.
- Loyalty rate among subscribers reaches 78%.

### Customer Segmentation
| Segment | Percentage |
|----------|----------|
| New Customers | 50% |
| Returning Customers | 35% |
| Loyal Customers | 15% |

---

## Business Recommendations

### Boost Subscription Programs
Offer exclusive benefits and incentives to encourage subscriptions.

### Strengthen Loyalty Programs
Reward repeat customers to improve retention and lifetime value.

### Targeted Marketing
Focus campaigns on high-revenue customer segments and express shipping users.

### Product Promotion
Feature top-rated products prominently in marketing campaigns.

---

## Project Workflow

```text
Data Collection
       ↓
Data Cleaning
       ↓
Feature Engineering
       ↓
PostgreSQL Integration
       ↓
Exploratory Data Analysis
       ↓
Visualization
       ↓
Business Insights & Recommendations
