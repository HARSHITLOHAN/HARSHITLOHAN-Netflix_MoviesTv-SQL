# 🎬 Netflix Data Analysis using SQL

Hi, I’m **Harshit Lohani**, a Computer Science Engineer currently learning **Data Analysis**.  
This is a hands-on SQL project where I explored Netflix's movie and TV show data to answer real business questions and strengthen my data skills.

---

## 📌 Project Goals

- Analyze content distribution (Movies vs TV Shows)
- Explore ratings, release years, durations, and genres
- Use SQL to solve real-world data problems
- Practice joins, CTEs, window functions, and string/date handling

---

## 📂 Dataset Source

📥 [Netflix Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)

---

## 🧱 Database Schema

```sql
CREATE TABLE netflix (
  show_id VARCHAR,
  type VARCHAR,
  title VARCHAR,
  director VARCHAR,
  casts VARCHAR,
  country VARCHAR,
  date_added VARCHAR,
  release_year INT,
  rating VARCHAR,
  duration VARCHAR,
  listed_in VARCHAR,
  description VARCHAR
);

---

## 🔍 Key SQL Questions Answered

1.Total Movies vs TV Shows
2.Most common rating for each type
3.Top 5 countries by content count
4.Longest movie by duration
5.Content added in last 5 years
6.All works by Rajiv Chilaka
7.TV Shows with >5 seasons
8.Top actors in Indian content
9.Classify titles as Good/Bad using keywords

💡 All queries are included in Solution Netflix.sql.

---

🧠 What I Learned

Writing clean, efficient SQL queries
Handling multi-valued fields and missing data
Thinking like a data analyst: structured questioning
Turning raw data into insights

---

👨‍💻 About Me
I’m Harshit Lohani, a CS Engineer exploring SQL, Excel, Python, and Power BI to become a data analyst.
I believe in learning by building — this project is one step forward in that journey.

📫 Email: lohaniharshit124@gmail.com
🔗 LinkedIn
🌐 GitHub Profile

