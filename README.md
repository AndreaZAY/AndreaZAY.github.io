## Table of contents
1. [About Me](#me)
2. [Portfolio](#portfolio)
    - [NLP: Sentiment Analysis on FY2022 10-K Reports from S&P 500 Companies](#fed)
    - [Regression Practice](#reg)
3. [Job Description and Career Objective](#career)
4. [My Hobbies](#hobbies)

---

---
## About Me  <a name="me"></a>

Hello! My name is Anyi Zheng, and I am a dedicated and enthusiastic student pursuing a Bachelor of Science in Business and Economics with a Business Analytics major and an Applied Mathematics major at Lehigh University. I am passionate about AI, finance, and technology, and I am excited to apply my skills and knowledge to positively impact the data analytics and quant industries.

# Sentiment Analysis of FY2022 10-K Reports from S&P 500 Companies
## Overview
How do Federal Reserve announcements influence the stock market according to Natural language processing, particularly the ETFs across various sectors?


This research conducts a detailed sentiment analysis of fiscal year 2022 (FY2022) 10-K reports filed by S&P 500 companies. The primary goal is to determine whether specific language within these reports carries positive or negative sentiment and to assess whether these sentiments correlate with the cumulative stock returns over two distinct timeframes following the filing dates. More specifically, the study investigates whether optimistic or pessimistic tones in 10-K filings are linked to superior or inferior stock performance.

## Data Description

### Data Sources and Samples
To carry out this analysis, 10-K reports for FY2022 were sourced from the Securities and Exchange Commission (SEC) database, and this dataset was integrated with the daily stock returns of S&P 500 firms. Cumulative returns after the filing dates were calculated for subsequent analysis. Sentiment evaluations were performed using multiple word lists, including the Loughran-McDonald Master Dictionary with Sentiment Word Lists (LM), Machine Learning (ML) sentiment lists, and other specialized dictionaries focusing on asset returns, climate-related terms, and financial constraints. The sentiment scores were then compared with the cumulative stock returns to explore potential relationships.

The findings reveal that while there are measurable correlations between sentiment scores and stock performance, these relationships lack statistical significance. Nevertheless, the insights gained from this research offer a foundation for future exploration of the interplay between textual sentiment in corporate reports and financial market responses. The study also underscores the importance of advancing analytical tools and methodologies to improve the accuracy and predictive power of sentiment analysis.

Dataset Details
Sources and Composition
The datasets used in this analysis are derived from several sources. The S&P 500 company list as of March 24, 2022, was retrieved from Wikipedia. The 10-K reports were downloaded from the SEC EDGAR database. Additional data support was obtained from Professor Donald Bowen’s 2023 FIN377 class repository at Lehigh University. This repository includes comprehensive resources such as unfiltered daily stock returns for 2022 in the crsp_2022_only.zip file and 2021 accounting information from 2021_ccm_cleaned.dta.

Data Preprocessing and Cleaning 
