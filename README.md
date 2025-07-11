# Zomato-Data-Analysis

# Objective:

In this hands-on data analysis project, I took on the role of a data analyst working for a food delivery and restaurant aggregator platform. The goal was to analyze Zomato’s restaurant dataset to uncover trends in customer preferences, order modes, dining costs, and restaurant performance. These insights can guide strategic decisions for improving user experience, targeting the right segments, and optimizing online vs. offline services.

# Dataset Overview

The dataset includes information across these key areas:

**Restaurant Info:** Name, Type of Restaurant (listed_in(type)), Online Order availability

**Customer Ratings:** Individual restaurant ratings and votes

**Pricing:** Approximate cost for two people

**Performance Metrics:** Total votes per restaurant

# Approach

**1. Data Loading & Cleaning**

Imported and reviewed the dataset using pandas and info() to check for missing values.

Cleaned the rate column by parsing text to float values to ensure consistent numeric analysis.

Verified that there were no null values remaining.

**2. Restaurant Type Exploration**

Visualized restaurant categories with countplot to identify the most common dining options.

Found that dining restaurants dominate the market share.

**3. Votes Analysis by Restaurant Type**

Grouped votes by restaurant type to see which categories attract the most customers.

Found that dining restaurants receive the highest engagement in terms of votes.

**4. High Performer Identification**

Identified the restaurant(s) with the highest number of votes to spotlight top performers.

**5. Online vs. Offline Ordering Trends**

Analyzed online_order availability to understand how many restaurants offer digital ordering.

Discovered that a majority of restaurants still rely on offline ordering.

**6. Ratings Analysis**

Checked the distribution of restaurant ratings using histograms.

Most restaurants have ratings between 3.5 and 4 — indicating strong overall customer satisfaction.

**7. Dining Cost Preferences for Couples**

Explored the approx_cost(for two people) feature to understand what price points couples prefer.

Found that most couples favor restaurants with an average cost around ₹300.

**8. Ratings: Online vs. Offline**

Compared ratings between restaurants with online ordering and those without.

Box plots revealed that restaurants with online orders tend to receive higher ratings.

**9. Order Mode vs. Restaurant Type**

Built a pivot table and heatmap to see how online ordering preferences vary by restaurant type.

Dining and quick bites restaurants show different patterns in adopting online orders.

# Key Insights

Dining restaurants are the most popular category both in count and total customer votes.

Online ordering is still underutilized by many restaurants, yet it correlates with higher average ratings — suggesting an opportunity for expansion.

Couples prefer moderately priced restaurants (around ₹300) for dining out.

Customer feedback is more positive for online ordering experiences compared to offline, highlighting the importance of digital convenience in food service.

# Tools & Libraries Used

**Python:** Core scripting

**pandas, numpy:** Data manipulation and cleaning

**matplotlib, seaborn:** Data visualization (bar plots, histograms, heatmaps, boxplots)

# Outcome

This project strengthened my ability to clean, transform, and explore real-world business data. It also sharpened my skills in visualizing key trends and delivering actionable insights — crucial for both data analyst and product analyst roles. By interpreting customer and restaurant behavior, I demonstrated how data-driven strategies can improve product offerings, boost customer satisfaction, and guide digital adoption decisions.
