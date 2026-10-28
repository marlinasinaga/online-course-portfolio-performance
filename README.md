# Online Course Portfolio Performance
An end-to-end data analytics project analyzing online course portfolio performance, revenue, learner demand, pricing, course quality, and completion rates using Microsoft Excel.

> **Project Context:** This project was developed as part of the final project for the **MySkill Data Analysis Bootcamp**.

## 1. Business Understanding
### Business Problem
Online learning platforms manage thousands of courses across different categories, platforms, pricing ranges, and course characteristics. Understanding which courses and portfolio segments are associated with stronger revenue and learner demand can support better portfolio management and pricing decisions.

This project analyzes the provided online course dataset to identify performance patterns across learner demand, revenue, course characteristics, pricing, and platforms.

### Business Objectives
- Evaluate revenue performance across platforms and course categories.
- Examine the relationship between learner enrollment and revenue.
- Analyze learner demand and completion rates across different course-duration ranges.
- Evaluate the distribution of courses across different portfolio segments.
- Identify areas that may provide opportunities for portfolio optimization.

### Business Questions
1. Which platforms generate the highest revenue?
2. Which course categories contribute the most to revenue?
3. Is higher learner enrollment associated with higher revenue?
4. How does course duration relate to learner demand and completion rate?
5. Which areas of the course portfolio may provide opportunities for further optimization?

## 2. Data Source

### Dataset Overview
The dataset was provided as part of the **MySkill Data Analysis Bootcamp Final Project**.

It contains **10,000 online courses** with information related to course categories, learner enrollment, pricing, revenue, ratings, completion rates, platforms, and geographic distribution.

### Key Metrics
| Metric | Value |
|---|---:|
| Total Courses | 10,000 |
| Total Revenue | $2.7B |
| Total Enrollments | 25.3M |
| Average Rating | 3.99 / 5 |
| Average Completion Rate | 75.12% |

### Main Data Dimensions
| Dimension | Variables |
|---|---|
| Course | Category, Main Category |
| Demand | Enrolled Students |
| Revenue | Price, Revenue |
| Quality | Rating, Completion Rate |
| Course Characteristics | Duration |
| Platform | Platform |
| Geography | State |
| Performance | Top Course |

## 3. Tools & Methodology
### Tools
- Microsoft Excel
- PivotTable
- PivotChart
- Slicer
- Excel Charts
- Excel Formulas
- Data Cleaning
- Descriptive Analysis

### Analytical Approach
The analysis follows an end-to-end analytical workflow:
**Raw Data → Data Preparation → Data Transformation → Exploratory Analysis → Dashboard → Insights → Recommendations**
The analysis was structured as a business case to translate descriptive patterns in the dataset into actionable business insights.

## 4. Data Preparation
The dataset was prepared for analysis by reviewing data consistency and creating additional analytical categories to support segmentation and comparison.

### Derived Variables
- **Duration Range**
- **Price Range**
- **Enrollment Range**
- **Revenue Segment**
- **Enrollment Segment**
- **Portfolio Segment**

These derived variables were used to compare course performance across different levels of learner demand, pricing, and revenue.

## 5. Exploratory Analysis
The analysis examines course portfolio performance across several dimensions:
- Revenue by Platform
- Revenue by Course Category
- Enrollment by Course Duration
- Completion Rate by Course Duration
- Average Revenue by Enrollment Range
- Course Distribution by Category
- Course Performance by Price Range

## 6. Key Findings
### Finding 1 — Higher Enrollment Is Associated With Higher Average Revenue
Average revenue increases consistently across enrollment ranges, from approximately **$57K** for courses with 0–1K enrollments to approximately **$477K** for courses with 4K–5K enrollments.
This pattern indicates a strong association between learner demand and revenue performance.

### Finding 2 — Platform Performance Differs Across the Portfolio
Revenue contribution varies across platforms, with some platforms generating higher revenue than others.
This suggests that platform performance is an important dimension to consider when evaluating course portfolio performance.

### Finding 3 — Revenue Contribution Varies Across Course Categories
Course categories contribute different levels of revenue, indicating that monetization is not evenly distributed across the course portfolio.
Categories with stronger revenue contribution may represent areas for further evaluation, while considering course volume and learner demand alongside revenue.

### Finding 4 — Course Duration Does Not Show a Clear Relationship With Completion Rate
Completion rates remain within a relatively narrow range across different course-duration groups, while enrollment varies more noticeably.
This suggests that longer course duration alone does not necessarily indicate stronger learner engagement.

## 7. Dashboard
The dashboard provides an interactive overview of course revenue, learner demand, platform performance, course categories, pricing, duration, and completion rates.

![Online Course Portfolio Performance](dashboard/dashboard.png)

## 8. Business Recommendations

### 1. Prioritize High-Demand Courses
Courses with stronger learner enrollment should receive greater attention in promotion and discoverability initiatives, as higher enrollment is associated with substantially higher average revenue.

### 2. Evaluate High-Performing Categories
Categories with strong revenue contribution should be evaluated for potential portfolio expansion while considering learner demand, course volume, rating, and completion rate.

### 3. Evaluate Pricing Together With Demand
Pricing performance should not be evaluated independently. Revenue and enrollment should be considered together when assessing pricing and monetization opportunities.

### 4. Use Multiple Performance Indicators
Portfolio decisions should consider multiple indicators, including **revenue, enrollment, completion rate, rating, pricing, and course characteristics**, rather than relying on a single performance metric.
