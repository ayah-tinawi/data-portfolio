# E-commerce Funnel Analysis

## Project Overview

This project analyzes user behavior across an e-commerce sales funnel using Google BigQuery and SQL.

The objective was to identify where users drop off during the purchasing journey, measure conversion rates between funnel stages, evaluate marketing channel performance, and generate business recommendations to improve revenue and customer acquisition.

---

## Business Questions

- Where do users drop off in the purchasing process?
- What are the conversion rates between funnel stages?
- Which traffic sources generate the highest conversions?
- How long does it take users to convert?
- What revenue metrics can be derived from customer behavior?

---

## Dataset

The dataset contains e-commerce user event data, including:

- Page Views
- Add to Cart Events
- Checkout Starts
- Payment Information Submissions
- Purchases
- Revenue Data
- Traffic Sources

The analysis focuses on user activity over a 30-day period.

---

## Tools Used

- Google BigQuery
- SQL
- Data Analysis
- Funnel Analysis

---

## Funnel Stages

The customer journey was analyzed through five stages:

1. Page View
2. Add to Cart
3. Checkout Start
4. Payment Information
5. Purchase

---

## Analysis Performed

### 1. Funnel Conversion Analysis

Calculated the number of users progressing through each stage of the sales funnel and measured conversion rates between stages.

### 2. Traffic Source Performance

Compared funnel performance across acquisition channels to identify the most effective marketing sources.

### 3. Time-to-Conversion Analysis

Measured the average time users take to move from viewing products to completing a purchase.

### 4. Revenue Analysis

Calculated key business metrics including:

- Total Revenue
- Total Buyers
- Total Orders
- Average Order Value (AOV)
- Revenue per Buyer
- Revenue per Visitor

---

## Key Findings

- The largest drop-off occurs between the Page View and Add to Cart stages.
- Users who reach the payment stage are highly likely to complete their purchase.
- Email traffic produces the strongest conversion performance.
- Social traffic drives volume but converts less efficiently than other channels.
- The checkout process appears effective, with strong conversion rates in the later funnel stages.

---

## Business Recommendations

### 1. Improve Product Page Engagement

The biggest loss of potential customers occurs before products are added to the cart.

**Recommendation:**

- Improve product descriptions and imagery.
- Highlight customer reviews and ratings.
- Test stronger call-to-action buttons.
- Optimize product page load speed.

### 2. Increase Investment in High-Converting Channels

Email marketing demonstrates stronger conversion performance than several other acquisition channels.

**Recommendation:**

- Expand email marketing campaigns.
- Implement newsletter sign-up incentives.
- Create abandoned-cart email sequences.
- Increase retention-focused email communication.

### 3. Improve Social Traffic Quality

Social channels generate traffic but convert at a lower rate.

**Recommendation:**

- Refine audience targeting.
- Use retargeting campaigns.
- Focus on lead generation and email capture.
- Test creative variations and landing pages.

### 4. Preserve Checkout Experience

Users who reach checkout and payment stages convert at a high rate.

**Recommendation:**

- Avoid unnecessary checkout redesigns.
- Continue monitoring checkout abandonment.
- Maintain a simple and frictionless payment process.

---

## SQL Skills Demonstrated

- Common Table Expressions (CTEs)
- Conditional Aggregation
- DISTINCT Counting
- Conversion Rate Analysis
- Timestamp Functions
- Revenue Metrics
- Funnel Analysis

---

## Project Files

- `funnel_analysis.sql` — Complete SQL analysis
- `user_events.csv` — Source dataset

---

## Skills Demonstrated

- SQL
- BigQuery
- Business Analytics
- Funnel Analysis
- Marketing Analytics
- Revenue Analysis
- Data Storytelling
