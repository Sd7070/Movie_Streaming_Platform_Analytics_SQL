# 🎬 Movie Streaming Platform Analytics

![Streaming Platform Analytics Banner](0_zdNurvD2F-Q18RQ-.png)

## 🎯 Project Overview
This project involves a comprehensive **SQL-based analysis** for a fictional movie streaming platform. The goal is to analyze user behavior, content performance, subscription trends, and revenue generation to drive data-driven decision-making.

By leveraging **advanced SQL queries**, this project explores:
- 📉 **Churn Analysis**: Identifying users at risk of leaving.
- 🎭 **Genre Popularity**: Understanding what content users engage with the most.
- 🕒 **Watch Habits**: Analyzing peak viewing times and binge-watching patterns.
- 💰 **Revenue Trends**: Tracking subscription types and payment success rates.

## ✨ Features
- **Exploratory Data Analysis (EDA)**: Initial data exploration to understand user demographics and catalog size.
- **Content Performance**: Analysis of watch time by genre and movie duration.
- **User Engagement**: Segmentation of users into High, Medium, and Low engagement categories.
- **Churn Prediction**: Identification of expired subscriptions and at-risk user cohorts.
- **Revenue Analytics**: Breakdown of revenue by plan type (Basic, Standard, Premium).

## 🗄️ Database Schema
The `StreamingDB` includes the following core tables:

| Table Name | Description |
|------------|-------------|
| **Users** | Demographics (name, email, gender, dob, signup_date). |
| **Movies** | Movie details (title, genre, duration, release_year). |
| **Subscriptions** | Plan types (Basic, Standard, Premium), costs, and active dates. |
| **WatchHistory** | Viewing logs (movie_id, watch_date, watch_duration). |
| **Reviews** | User ratings and textual reviews. |
| **Revenue** | Payment transactions and methods. |


## 🛠️ Technologies Used
- **SQL** (MySQL / PostgreSQL compatible)
- **Data Engineering**: Schema design, Data normalization
- **Key SQL Features**:
  - `GROUP BY` & `HAVING` for aggregations
  - `JOIN`s for relating users, movies, and streams
  - `CASE` statements for segmentation
  - `Window Functions` for ranking and trends
  - `Subqueries` & `CTEs` for complex logic

## 🚀 Getting Started
### Prerequisites
- SQL Client (MySQL Workbench, DBeaver, pgAdmin)
- Local Server (XAMPP, PostgreSQL, etc.)

### Installation Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Movie-Streaming-Analytics.git
   ```
2. **Import the Database**:
   - Open `Movie_Streaming_Platform_Analytics.sql` in your SQL client.
   - Run the script to create the schema and populate the tables.
3. **Run Analysis**:
   - Scroll to the bottom of the SQL file to find the analytical queries and insights.

## 📈 Analysis Highlights
### 1. Genre Popularity
- **Horror** and **Drama** dominate watch time, while **Action** underperforms despite high availability.
- **Documentaries** show strong engagement from a dedicated niche audience.

### 2. Churn Risk
- **286 users** have expired subscriptions. A cluster of expirations in **mid-2025** suggests potential issues with pricing or content quality during that period.

### 3. User Segmentation
- Users are categorized by watch time. A significant portion of the base has **0 watch time**, indicating a need for better onboarding or "first-watch" incentives.

### 4. Subscription Trends
- **Premium** plans are the highest revenue drivers but come with higher churn sensitivity.
- A sharp drop in viewing activity in **September 2025** was identified, warranting technical investigation.

## 📝 Notes
- The dataset is synthetic and designed for educational purposes.
- Queries are written in standard SQL and should work across most major relational database systems.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!
