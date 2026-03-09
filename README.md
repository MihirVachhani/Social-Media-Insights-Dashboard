# 📱 Social Media Insights Dashboard

> A multi-platform social media analytics dashboard combining Excel business intelligence and Python EDA — built to help recruiters, clients, and marketing teams make data-driven decisions.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Data Source](#data-source)
- [Key Metrics](#key-metrics)
- [Features & Highlights](#features--highlights)
- [Excel Dashboard](#excel-dashboard)
- [Python Analysis](#python-analysis)
- [Key Insights](#key-insights)
- [Business Impact](#business-impact)
- [Future Improvements](#future-improvements)
- [What I Learned](#what-i-learned)

---

## 🔍 Overview

The **Social Media Insights Dashboard** consolidates data from **Instagram, X (Twitter), YouTube, Facebook, and LinkedIn** into one unified view. Based on **550 posts** published between **January 2024 and October 2024**, it helps marketing teams quickly understand:

- 📈 How content performs across platforms
- 👥 Where audience growth is happening
- 🎯 Which content attracts the most engagement
- ⏰ When to post for maximum impact

The project delivers insights through two complementary tools:

| Tool | Purpose |
|------|---------|
| 📊 Excel Dashboard | Business monitoring & interactive reporting |
| 🐍 Python Notebook | Deeper exploratory data analysis (EDA) |

---

## 🛠️ Tech Stack

### Data Analysis

- 🐍 **Python** — Core programming language
- 🧮 **Pandas** — Data manipulation and analysis
- 📉 **Matplotlib** — Data visualization
- 🎨 **Seaborn** — Statistical data visualization
- ☁️ **Google Colab** — Cloud-based notebook environment

### Dashboard & Visualization

- 📊 **Excel** — Main dashboard platform
- 📈 **Pivot Tables** — Dynamic aggregation and analysis
- 🔄 **Power Query** — Data cleaning and transformation
- 🎨 **Conditional Formatting** — Highlight trends and thresholds
- 🧩 **KPI Cards, Slicers, Heatmaps, Charts** — Interactive insights

---

## 📂 Data Source

- **Type:** Custom-generated and structured by the author
- **Scope:** 550 posts across 5 platforms — Instagram, X (Twitter), YouTube, Facebook, LinkedIn
- **Period:** January 2024 – October 2024
- **Structure:** 4 sheets covering post type, impressions, engagement, follower growth, and posting time
- **Preparation:** Refined using AI tools to ensure consistency and completeness

---

## 📏 Key Metrics

| Metric | Formula | Description |
|--------|---------|-------------|
| **Engagement Rate** | `Total Engagement / Reach` | Measures how actively audiences interact with content |
| **Engagement Efficiency** | `Total Engagement / Impressions` | Shows how effectively impressions convert into engagement |
| **Follower Growth Rate** | `New Followers / Followers at Post Time` | Measures audience growth relative to current follower base |
| **Net Follower Growth** | `New Followers − Unfollows` | Real audience growth after accounting for churn |

---

## ✨ Features & Highlights

### Business Problem
Companies and marketing teams often struggle with scattered social media data. Metrics like impressions, engagement, and follower growth vary across platforms — making it difficult to compare performance, identify trends, or plan optimal content strategies.

### Solution
This dashboard combines multi-platform data into one interactive view, delivering actionable insights by:

- ✅ Tracking overall growth and engagement trends
- ✅ Comparing performance across platforms and content categories
- ✅ Highlighting reach, impressions, and follower growth patterns
- ✅ Revealing the best posting times to maximize engagement

---

## 📊 Excel Dashboard

An interactive Excel dashboard designed for real-time social media monitoring.

> 🔗 **Dashboard Preview:** [View Dashboard Snapshot](https://github.com/MihirVachhani/Social-Media-Insights-Dashboard/blob/main/Snapshot%20of%20Excel%20DashBoard.png)

### KPI Cards
- Total Posts
- Total Followers
- Total Engagement
- New Followers (Last 30 Days)
- Engagement (Last 30 Days)

### Charts & Visuals

| Visual | Description |
|--------|-------------|
| 📊 Posts per Platform (Column Chart) | Activity distribution by platform |
| 🥧 Posts per Content Category (Pie Chart) | Content type breakdown |
| 📋 Post Type vs Platform — Avg. Impressions | Content reach comparison |
| 📋 Content Category vs Platform — Avg. Engagement | Engagement quality by platform |
| 📈 Reach & Engagement Trend (Line Chart) | Growth momentum over time |
| 👥 Net Follower Growth by Month | Monthly audience expansion |
| 🔥 Best Posting Time Heatmap | Engagement optimization by day & hour |

---

## 🐍 Python Analysis

A Python notebook performs deeper EDA to answer real-world marketing questions.

### Analysis Areas

- **Platform Performance** — Which platforms generate the most reach, engagement, and followers?
- **Content Strategy** — Which post types and content categories perform best?
- **Audience Growth** — Follower growth trends across platforms and months
- **Posting Strategy** — Best day and time to post for maximum engagement
- **Engagement Efficiency** — How effectively impressions convert into engagement

### Key Findings

| Question | Finding |
|---------|---------|
| 🏆 Most Impressions | **X (Twitter)** generates the highest impressions |
| 👥 Most New Followers | **X (Twitter)** leads in follower growth |
| 📅 Highest Growth Month | **August** recorded the highest follower growth |
| ❌ Most Unfollows | Instagram: **Meme** content · X: **Personal** posts |
| 🎬 Highest Engagement Rate | **Short-form videos** (Reels & Shorts) |
| ⚡ Best Engagement Efficiency | **Facebook** converts impressions most effectively |
| 🏅 Top Category per Platform | Trend content → Facebook, Instagram, YouTube · Educational → LinkedIn |
| 📈 Highest Follower Growth Rate | **Facebook** at **22%** |
| 🧲 Most Follower-Attracting Category | **Meme** content |
| ⏰ Best Posting Time | **Thursday 06:00–08:00** · Runner-up: Sunday 08:00–10:00 |

### ⭐ Top Performing Posts

The notebook identifies the **Top 10 highest-engagement posts**. Common patterns among top performers:

- 🎥 Video-based formats
- 📚 Educational themes
- 🔥 Trending topics
- 💬 Personal storytelling

---

## 📈 Key Insights

```
✔  X (Twitter) brings the biggest reach — Facebook builds stronger growth
✔  Videos work best everywhere: Reels, Shorts, and long-form all outperform other formats
✔  Facebook is the fastest-growing platform with a 22% follower growth rate
✔  Trending topics attract new followers quickly
✔  Thursday morning (06:00–08:00) and Sunday morning (08:00–10:00) drive peak engagement
```

---

## 💼 Business Impact

| Use Case | Value Delivered |
|---------|----------------|
| 🎯 **Recruitment Branding** | Showcase social media strength to recruiters and clients |
| 📣 **Campaign Optimization** | Identify platforms and content with highest ROI |
| 👥 **Audience Growth Strategy** | Track follower trends and adjust posting frequency |
| ⏰ **Content Scheduling** | Use the heatmap to post at proven high-engagement times |
| 🎬 **Video Insights** | Measure retention and replays to refine creative strategy |

---

## 🚀 Future Improvements

- [ ] Add **predictive analytics** for audience growth forecasting
- [ ] Build a **video-only dashboard** for deeper retention and replay insights
- [ ] Integrate **advanced charting** with combined views and interactive overlays

---

## 📚 What I Learned

Through this project I developed skills in:

- 🗂️ Designing structured datasets for multi-platform analytics
- 📊 Building interactive Excel dashboards for business users
- 🐍 Performing exploratory data analysis using Python and Pandas
- 💡 Generating actionable marketing insights from raw data
- 🎨 Communicating findings through visual storytelling

---

## 📁 Project Structure

```
📦 social-media-insights-dashboard
 ┣ 📊 Social_Media_Dashboard.xlsx     # Interactive Excel Dashboard
 ┣ 📓 Social_Media_Analysis.ipynb     # Python EDA Notebook
 ┣ 📂 data/
 ┃ ┗ 📄 social_media_data.csv         # Source dataset
 ┗ 📄 README.md
```

---

## 🤝 Connect

> If you find this project useful, feel free to ⭐ star the repo and share your feedback!

---

*Built with 💡 curiosity and 📊 data — January to October 2024*
