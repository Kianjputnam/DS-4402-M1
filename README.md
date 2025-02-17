# NBA Rookie Sentiment Analysis  

## Goals and Theories

Motivation and Context: 
Statistics like PER, Win Shares, and Plus-Minus are widely used to measure a player’s performance on the court, but scouting reports offer qualitative evaluations that capture traits/intangibles/potential like basketball IQ, work ethic, clutch, coachability,  and instincts—attributes that don’t always show up in box scores. Despite their importance in draft decisions, little research has tested whether the sentiment in pre-draft scouting reports can actually predict rookie performance in the NBA.

Hypothesis
Pre-draft scouting report sentiment correlates with rookie performance.

Research Question: 
Do the sentiment scores of the 2023 NBA rookie pre-draft scouting reports correlate with the players’ performance metrics in their rookie season?

## Software and Platform

### Required Software:  
- Python 3.x 
- Jupyter Notebook (or any Python IDE)  

### Required Packages:  

Ensure you have the following Python libraries installed:  

pip install pandas numpy seaborn matplotlib nltk wordcloud scipy statsmodels

### Platform used

Windows

## 📂 Repository Contents  
NBA-Rookie-Sentiment-Analysis

📂 DATA_folder

  - Reference_stats1.xlsx
  
  - Reference_stats2.xlsx
  
  - merged_nba_rookie_data.csv
  
  - merged_nba_stats2.csv
  
  - rookie_data_textblob.csv
  
  - rookie_data_vader.csv
  
  - scouting_reports.csv
  
📂 OUTPUT_folder

  - compound_distribution.png
  
  - eda.py
  
  - sentiment_boxplot.png
  
📂 SCRIPTS_folder
 
  - Compiling_stats_code.ipynb
  
  - Sentiment_Analysis_Correlations.ipynb
 
  - merge.py
  
  - scraper.py

  - textblob_analysis.ipynb
  
📂 PLANSandREFERENCES_folder

  - Project 1 M1.docx
  
  - Project 1 M2 (1).docx

  - Project 1 M4.pdf

📊 LICENSE.md # Licensing information

📊 README.md # Overview of the repository


## Reproducing Results

- Our NBA stats data came from NBA.com and NBAReference.com. They are found in Reference_stats1.xls and Reference_stats2.xls which were merged using Compiling_stats_code.ipynb to form merged_nba_stats2.csv (if reference stats are not working properly due to excel reading error, you can just refer to merged_nba_stats2.csv)

- scraper.py was used to get the scouting reports online and were turned into scouting_reports.csv, which was then compiled into merged_nba_rookie_data.csv

- textblob_analysis.ipynb was performed and compiled to rookie_data_textblob.csv

- Sentiment_Analysis_Correlations.ipynb was performed on rookie_data_textblob.csv and displays our findings. This also contains most of the figures shown in our presentation
