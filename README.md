# 📊 YouTube Data Scraper Analysis Project  
_Scraping, Analyzing & Visualizing YouTube Data using the YouTube Data API_

![Image]()

---

## 📑 Table of Contents  
1. [Overview](#overview)  
2. [Project Workflow](#project-workflow)  
3. [Business Problem](#business-problem)  
4. [Tools & Technologies](#tools--technologies)  
5. [Project Preparation](#project-preparation)  
6. [Scrape, Analyze and Visualization Channels Statistics](#scrape-analyze-and-visualization-channels-statistics)  
7. [Deep-dive into ‘T-Series’ channel](#deep-dive-into-t-series-channel)  
8. [Key Findings and Insights](#key-findings-and-insights)  
9. [Final Recommendations](#final-recommendations)  
10. [Key Outcomes](#key-outcomes)  
11. [Conclusion](#conclusion)  
12. [Author & Contact](#author--contact)  

---

## 📌 Overview  
This project leverages the **YouTube Data API** to scrape, analyze, and visualize statistics of popular YouTube channels.  
The workflow covers **data extraction, cleaning, exploratory data analysis (EDA), and visualization**.  

A special case study on the **‘T-Series’ channel** demonstrates how large-scale content production affects reach and engagement.  

---

## 🔄 Project Workflow  
1. Read and understand **YouTube API documentation**.  
2. Generate **YouTube API Key**.  
3. Create **virtual environment** & install dependencies.  
4. From **top 50 YouTube channels**, select **15 channels** based on subscriber count.  
5. Scrape, analyze, and visualize channel statistics.  
6. Perform a **deep-dive into ‘T-Series’ channel** for detailed insights.  

---

## 💡 Business Problem  
YouTube is one of the largest digital platforms where content drives audience engagement and brand visibility.  
Businesses, creators, and marketers need **data-driven insights** to:  
- Identify growth drivers for successful channels.  
- Benchmark against top competitors.  
- Optimize strategies for content publishing, reach, and audience engagement.  

This project addresses these questions by analyzing real YouTube data through Python and APIs.  

---

## 🛠 Tools & Technologies  
- **Environment:** Jupyter Notebook  
- **Programming Language:** Python  
- **Libraries:**  
  - Data Handling → `numpy`, `pandas`  
  - Visualization → `matplotlib`, `seaborn`  
  - API Integration → `googleapiclient`  
  - Text Formatting → `textwrap`  

---

## ⚙️ Project Preparation  
- **Understand YouTube API documentation:** [YouTube API Docs](https://developers.google.com/youtube/v3)  
- **Generate API Key:** Use Google Cloud Console to enable the YouTube Data API.  
- **Create Virtual Environment & Install Dependencies:**  
  ```bash
  python -m venv venv
  source venv/bin/activate   # On Windows: venv\Scripts\activate
  pip install -r requirements.txt

## 📈 Scrape, Analyze and Visualization Channels Statistics  
- Extracted channel-level statistics: **Subscribers, Total Views, Total Videos**.  
- Selected **15 top channels** (from top 50) based on subscribers.  
- Conducted **Exploratory Data Analysis (EDA):**  
  - Bar plots of subscribers, views, and uploads.  
  - Scatter plots to study correlations.  
  - Histograms for distribution insights.  
- **Key Observations:**  
  - High subscriber counts don’t always mean more uploads.  
  - Strong correlation between **total views** and **subscriber count**.  

---

## 🔍 Deep-dive into ‘T-Series’ channel  
A focused analysis on **T-Series**, the most subscribed channel on YouTube.  

**Insights:**  
- A few videos dominate views (>1.6B) → heavy-tailed distribution.  
- **Likes vs Views correlation:** ≈ 0.92.  
- **Comments vs Likes correlation:** ≈ 0.88.  
- Upload trends:  
  - Peak performance in **2018–2020**.  
  - Post-2021 uploads increased while average views declined.  
- Seasonality:  
  - April = highest uploads (9–10%).  
  - November = lowest uploads.  

---

## 📊 Key Findings and Insights  
- Top creators balance **volume + quality**.  
- Large subscriber base ≠ guaranteed engagement per video.  
- T-Series growth = **high upload frequency** + **regional content dominance**.  
- Engagement metrics strongly correlate but vary across content types.  

---

## ✅ Final Recommendations  
- **For Creators:**  
  - Upload consistently.  
  - Prioritize content that maximizes **viewer retention**.  
- **For Brands/Marketers:**  
  - Partner with channels showing **steady growth** and **high view-to-subscriber ratios**.  
- **For Researchers:**  
  - Extend analysis to **sentiment & audience demographics**.  
- **For Platform Strategy:**  
  - Monitor **regional content trends** to forecast audience shifts.  

---

## 🏆 Key Outcomes  
- Built a full **end-to-end pipeline** for YouTube data extraction.  
- Analyzed **15 top channels** with subscriber-based selection.  
- Extracted insights into growth, engagement, and content strategies.  
- Conducted an in-depth **T-Series case study** confirming its dominance.  

---

## 📌 Conclusion  
- Python + APIs are powerful for **real-world digital data analysis**.  
- Explained **why top channels dominate YouTube**.  
- Framework can extend to:  
  - **Automated monitoring** of channels.  
  - **Performance prediction** models.  

---

## 👤 Author & Contact  
**Author:** [Your Name]  
📧 Email: your.email@example.com  
💼 LinkedIn: [My LinkedIn Profile](https://www.linkedin.com/in/bhaskar-pal-2k02/)  
💼 Portfolio: [My Portfolio](https://bhaskarpal1707.github.io/portfolio/)  

