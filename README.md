# 🔹 BigQuery & GA4 Analytics Projects

This repository contains sample data analytics projects using BigQuery and GA4, including SQL queries for analysis.

---

## 1. Conversion Analysis by Date & Traffic Channel (Medium Level)
- SQL query for a table tracking conversions from session start to purchase.
- **Metrics:** `user_sessions_count`, `visit_to_cart`, `visit_to_checkout`, `visit_to_purchase`
- **SQL file:** [conversion_analysis.sql](sql/conversion_analysis.sql)

---

## 2. Landing Page Conversion Comparison (Medium+ Level)
- SQL query comparing the performance of different landing pages.
- **Metrics:** number of unique sessions, purchases, and conversion rates for 2020
- **SQL file:** [landing_page_comparison.sql](sql/landing_page_comparison.sql)

---

## 3. Engagement vs Purchase Correlation (Hard Level)
- SQL query analyzing user engagement: calculated `engagement` for each session, activity time, and purchase occurrence.
- Computed the correlation coefficient between engagement and purchase.
- **SQL file:** [engagement_vs_purchase.sql](sql/engagement_vs_purchase.sql)

---

**Note:** All SQL files are safe to share publicly and can be run in BigQuery with anonymized or sample datasets.
