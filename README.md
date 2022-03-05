# 
## Samachar: News Media on Air Pollution in India

<hr>
This repository contains codes (Jupyter Notebooks) to reproduce the figures and results of our submission under review at COMPASS-2022. Each folder represents a section in the paper. <br></br>

- **Section Overview**

|**Section**|**Title**|**Decription**|
|--|--|--|
|3|[Dataset](dataset)|We are making the News-articles-dataset public. (**Note**:  PM25 data is publicly available in [CPCB](https://app.cpcbccr.com/ccr/#/caaqm-dashboard-all/caaqm-landing/caaqm-data-availability) portal and [OpenAQ](https://openaq.org/#/) website.)|
|5.1|[Research-Question-1](Research_Question_1)|How do news media respond to air pollution?|
|5.2|[Research-Question-2](Research_Question_2)|What are the air pollution related topics discussed by news media? (Topic Modeling)|

<br></br>
- **Tables/Figures**

|Figure/Table|File/Folder| Decription |
|--|--|--|
|Figure 1 |[dataset/Figure-1_Number-of-cities-for-pm25-data-available.ipynb](dataset/Figure-1_Number-of-cities-for-pm25-data-available.ipynb)|To plot number of cities along with time for which PM25 data is available.|
|Figure 2|[dataset/Figure-2_TOI-vs-Hindu-articles_over_time.ipynb](dataset/Figure-2_TOI-vs-Hindu-articles_over_time.ipynb)|To plot articles of TOI and The Hindu over time (2010-21).|
|Figure 3 |[Research_Question_1/Figure-3_Choropleth_map_PM25_and_articles.ipynb](Research_Question_1/Figure-3_Choropleth_map_PM25_and_articles.ipynb)|Python Notebook to generate Choropleth map of India showing PM<sub>2.5</sub> level and number of news articles|
|Figure 4|[Research_Question_1/Figure-4_Violation_of_India_limit_by_IGP.ipynb](Research_Question_1/Figure-4_Violation_of_India_limit_by_IGP.ipynb)|Time series of PM<sub>2.5</sub> level and Number of articles for Delhi|
|Figure 5|[Research_Question_1/Figure-5_timeseries_of_aq_articles_delhi.ipynb](Research_Question_1/Figure-5_timeseries_of_aq_articles_delhi.ipynb)|Time series of PM<sub>2.5</sub> level and Number of articles for Delhi|
|Table 3|[Research_Question_1/Table-3,4_pollution-in-IG-Plain_and_Delhi-time-series.ipynb](Research_Question_1/Table-3,4_pollution-in-IG-Plain_and_Delhi-time-series.ipynb)|PM<sub>2.5</sub> and articles of Cities of Indo Gangetic (IG) plain|
|Table 4|[Research_Question_1/Table-3,4_pollution-in-IG-Plain_and_Delhi-time-series.ipynb](Research_Question_1/Table-3,4_pollution-in-IG-Plain_and_Delhi-time-series.ipynb)|PM<sub>2.5</sub> and articles of 10 most highlighted cities in News-media|
|Figure 6 |[Research_Question_2/Figure-6_Topic-Modeling-tarining-LDA-model.ipynb](Research_Question_2/Figure-6_Topic-Modeling-tarining-LDA-model.ipynb)|Train LDA Topic modeling model using `gensim` and create visualization [LDA_topic_modelling_Visualization.html](https://ouranonymoussubmission.github.io/Samachar-News-media-on-air-pollution/Research_Question_2/LDA_Visualization/LDA_topic_modelling_Visualization.html) using pyLDAvis.|
|Figure 7|[Research_Question_2/Figure-7_Topic-evolution-over-time.ipynb](Research_Question_2/Figure-7_Topic-evolution-over-time.ipynb)|Frequency of articles of topic over time |
|Figure 8|[Research_Question_2/Figure-8_Open-fire-vs-Stubble-burning-articles.ipynb](Research_Question_2/Figure-8_Open-fire-vs-Stubble-burning-articles.ipynb)|Timeseries of NASA Open Fire cout data (VIIRS) [`firedata`](Research_Question_2/firedata) to identify when stubble burning is happening and compare firecount|
|Figure 9|[Research_Question_2/Figure-9_Source-contribution-Delhi.ipynb](Research_Question_2/Figure-9_Source-contribution-Delhi.ipynb)|Comparison of Sources contribution to PM<sub>2.5</sub> in Delhi and articles relavent to particular sources, to verify if media discussion is in consonance with source contribution.|
