# Sum(Text)

Text summarizer specifically for summarizing news articles

## Description

When you open news sites, do you just start reading every news article? Probably not. People typically glance at the short news summary and then read more details if interested. Short, concise and informative summaries can help to select preferred news articles more efficiently and accurately. However, manual text summarization is a time-expensive task. The automation of the summarization task has been gaining increasing popularity.

This project aims to implement and experiment with various models that can make automatic text summarization specifically on news articles to provide concise and accurate news summaries to people.

## Structure

### **Demo**

* Summarizer demo built with Gradio (SumText_Demo.ipynb)

### **Data**

#### data_ver1

* Training, validation, and test data (training_data.csv, validation_data.csv, test_data.csv)

#### recent_news

* Web-scraping script (Data_Scraping.ipynb)
* Scraped recent news articles from BBC (bbc_news.csv)
* Updated data preprocessing script (Recent_News_Data_Update.ipynb)
* Final version of recent news data (bbc_news_updated.csv)

#### Manual Scoring

* Manual Scoring Results (Final scoring.xlsx)

### **Experiments _ Results**

* Decoding methods experiment script (Decoding_Experiments.ipynb)
* Script that generates results for recent news data (Generated_Results.ipynb)

### Extractive Baseline Model 
* Baseline_extractive_first3.ipynb

### GPT2 Baseline Model 
* Baseline_GPT2.ipynb

### T5-base Model 
* T5_base.ipynb

### BART-base Model 
* BART_base.ipynb

## Authors

Contributors names 

* Yichen Zhang
* Zijie Zhao
