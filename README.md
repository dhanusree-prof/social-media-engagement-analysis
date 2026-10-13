# Social Media Engagement Analysis

## Project Overview

This project analyzes a synthetic dataset of 1,200 social media posts from 2025 to explore engagement performance, content patterns, and posting schedules.

The project demonstrates an end-to-end data analytics workflow using Excel, Python (Google Colab), and Power BI.

**Important:** The dataset is synthetic and does not represent verified activity from a real company or social media account.

## Objectives

* Validate and prepare social media data.
* Calculate engagement metrics.
* Compare performance across platforms, content types, and themes.
* Explore engagement patterns by day, month, hour, and time period.
* Develop an interactive Power BI dashboard.
* Provide data-informed recommendations for further testing.

## Tools Used

* **Microsoft Excel:** Data checks, pivot tables, and summary analysis.
* **Python (Google Colab):** Data validation, calculations, grouped analysis, and charts.
* **Power BI Desktop:** Interactive dashboard and visual reporting.

## Key Metrics

* **Total posts:** 1,200
* **Total engagement:** 1,536,305
* **Average engagement per post:** 1,280.25
* **Average engagement rate:** 5.25%

Total engagement is calculated as likes + comments + shares + clicks. Engagement rate is calculated as total engagement divided by reach, multiplied by 100.

## Key Findings

* Instagram recorded higher average engagement and average engagement rate than Facebook in this synthetic sample.
* All ten posts ranked highest by total engagement were Instagram Reels.
* Behind the Scenes had the highest average engagement among the analyzed themes.
* Sunday had the highest average engagement rate among weekdays.
* 7 PM had the highest average engagement among observed posting hours.
* November had the highest average engagement per post among months.

These are descriptive findings from synthetic data. They do not establish that a particular platform, content type, theme, or posting time causes higher engagement.

## Project Files

* `Social_Media_Engagement_Analysis.ipynb` — Python analysis notebook.
* `Social_Media_Clean_Data.csv` — cleaned dataset with derived fields and engagement metrics.
* `charts/` — visualizations generated in Python.
* `report/` — project report.
* `powerbi/` — interactive Power BI dashboard, if included.
* `excel/` — Excel analysis workbook, if included.

## Recommendations

* Validate the observed patterns using real social media account data.
* Test content formats and posting schedules over multiple weeks.
* Compare engagement rate, total engagement, and reach consistently.
* Treat the findings as hypotheses for further testing rather than guaranteed outcomes.

## Limitations

The dataset is synthetic. Posting volumes vary across categories and time periods, and some hours have no observations. The results are exploratory and cannot establish causal relationships.

## Project Status

Completed as a data analytics internship project.

