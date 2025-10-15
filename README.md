# YouTube Channel Growth Strategy Analysis

This project, developed using Python and Pandas, focuses on transforming raw data from the world's 1,000 most-subscribed YouTube channels into actionable Business Analytics insights.

Instead of building a prediction model, the goal is to define key performance indicators (KPIs) and use them to generate a strategic report on content efficiency and market niches for a media or content strategy team.

---

## View the Analysis & Report

| Format | Access Link | Notes |
| :--- | :--- | :--- |
| **Interactive Charts** | [**Launch Interactive Analysis in Google Colab**](https://colab.research.google.com/drive/1KWbPhhM1t9DsYrFLfeY8FtzgBkLe9gwV) | *Click here to view the notebook with the fully **interactive Plotly charts**.* |
| **Static PDF Report** | [**View Static PDF Report**](https://github.com/jordynsilvers/YouTube-Growth-Strategy-Analysis/blob/main/Copy%20of%20YoutubeDataVisualization.ipynb%20-%20Colab.pdf) | *A complete, static document of all code and chart outputs.* |

---

## Project Goals

* **KPI Engineering:** Create new metrics to measure content quality and channel longevity that go beyond simple subscriber count.
* **Strategic Analysis:** Identify the most successful content categories based on median performance, rather than just mean performance (which is easily skewed by outliers).
* **Correlation Mapping:** Quantify the relationship between channel age and content performance to inform long-term investment strategies.

---

## Analytical Insights

The analysis identified key strategic correlations critical for investment decisions:

* **Category Performance:** Identified the top 10 categories based on a combination of Median Subscribers and Content Efficiency (Avg. Views per Video), revealing which niches, such as **Music**, have the highest barrier to entry.
* **Content Efficiency:** Channels demonstrated a **weak positive (0.0866)** correlation between longevity (age) and high average views per video. This suggests that sustained content quality improves with time and experience, though the relationship is not very strong.
* **Strategic Gaps:** The analysis revealed categories with high subscriber counts but low content efficiency, indicating potential business opportunities for content partners to optimize video output and viewer engagement.

---

## Technology Stack

| Tool | Purpose |
| :--- | :--- |
| **Python** | Primary programming language. |
| **Pandas** | Essential library for all data manipulation, cleaning, KPI creation, and strategic grouping (`groupby`). |
| **Colab** | Environment used for iterative development and final presentation of the analysis. |

---

## Repository Structure

| File | Description |
| :--- | :--- |
| **YoutubeDataVisualization.ipynb** | The main Jupyter Notebook containing all data cleaning, feature engineering (KPI creation), strategic analysis, and reporting code. |
| **Copy of YoutubeDataVisualization.ipynb - Colab.pdf** | The exported static PDF report of the complete notebook. |
| **README.md** | Project overview and summary of findings (this file). |
| **most_subscribed_youtube_channels.csv** | The primary dataset used for this analysis. |
