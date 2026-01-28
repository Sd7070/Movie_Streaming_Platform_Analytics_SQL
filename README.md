# 🎬 Movie Streaming Platform Analytics

![Streaming Platform Analytics Banner](0_zdNurvD2F-Q18RQ-.png)

## 📌 Project Overview
This project involves a comprehensive **SQL-based analysis** for a fictional movie streaming platform. The goal is to analyze user behavior, content performance, subscription trends, and revenue generation to drive data-driven decision-making.

By leveraging **advanced SQL queries**, this project explores:
- 📉 **Churn Analysis**: Identifying users at risk of leaving.
- 🎭 **Genre Popularity**: Understanding what content users engage with the most.
- 🕒 **Watch Habits**: Analyzing peak viewing times and binge-watching patterns.
- 💰 **Revenue Trends**: Tracking subscription types and payment success rates.

## 📂 Database Schema
The project uses a relational database named `StreamingDB` with the following key tables:

| Table Name | Description |
|------------|-------------|
| **Users** | Stores user demographics (name, email, gender, dob, signup_date). |
| **Movies** | Contains movie details (title, genre, duration, release_year). |
| **Subscriptions** | Tracks user subscription plans (Basic, Standard, Premium), cost, and dates. |
| **WatchHistory** | Logs user viewing activity (movie_id, watch_date, watch_duration). |
| **Reviews** | Stores user ratings and review text for movies. |
| **Revenue** | specific payment transactions and methods. |

## 📊 Key Insights & Analysis
### 1. Genre Popularity & Viewing Behavior
- **Horror** and **Drama** are the most engaged genres, having the highest total watch minutes.
- **Action** movies have lower retention despite high availability, suggesting a need for better content or marketing.
- **Documentaries** have a surprising niche audience with high engagement.

### 2. Churn Risk Analysis
- **286 users** have expired subscriptions that haven't been renewed.
- A significant number of expirations are clustered around **mid-2025**, indicating potential pricing or content dissatisfaction during that period.
- **Action Strategy**: Targeted win-back campaigns and discount offers are recommended for this cohort.

### 3. User Engagement Segmentation
- The user base is segmented into **High, Medium, and Low** engagement levels.
- A large portion of users falls into the "Low Engagement" bucket (some with 0 watch time).
- **Opportunity**: Implement onboarding emails and personalized "Top 10" recommendations to activate dormant users.

### 4. Revenue & Subscription Trends
- **Premium** plans drive the most revenue but have higher expectations for content updates.
- **Monthly Viewing Trends**: Stable viewing from Jan-Aug 2025, but a sharp drop in **September 2025** requires investigation (potential technical outage or catalog removal).

## 🚀 How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Movie-Streaming-Analytics.git
   ```
2. **Import the Database**:
   - Open your SQL client (MySQL Workbench, DBeaver, etc.).
   - Run the script `Movie_Streaming_Platform_Analytics.sql` to create the schema and populate data.
3. **Run Queries**:
   - Execute the analysis queries found at the bottom of the SQL file to reproduce the insights.

## 🛠️ Tech Stack
- **Database**: MySQL / PostgreSQL (Compatible with standard SQL)
- **Tools**: SQL Workbench, Data Visualization (Tableau/PowerBI optional)

---
*Created for portfolio demonstration of SQL Analytics capabilities.*
