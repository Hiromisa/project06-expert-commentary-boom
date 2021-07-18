# Project: expert commentary boom in Japan

This is a project for Lede week6. I scraped three Japanese media's website to analyze "experrt commentary feature", which is booming in Japan.

## article based on this project
https://docs.google.com/document/d/1IvSf1imNVKOLRmiU_Vb7Dx7YuCV_9D14PCsF5x4PxNY/edit?usp=sharing

---
## Data
1. I created "experts list" through three media's webcite: [Nikkei](https://www.nikkei.com/think-all-experts), 
[Asahi](https://www.asahi.com/comment/), [NewsPicks](https://newspicks.com/recommended).
I generated three files titled ”nikkei.csv””asahi.csv””np.csv”. 

2. I added gender and a part of in-house experts information manually. 
Formatted csv files are titled: "formatted_expertcommentary - nikkei.csv","formatted_expertcommentary - asahi.csv","formatted_expertcommentary - newspicks.csv"

---
## Analysis
"comment_nikkei.ipynb", "comment_asahi.ipynb", "comment_NP.ipynb" contains my scraping process, wrritten in Python. Relevant outputs can be found there.
"expert_commentary_analysis.ipynb" contains my entire analysis, wrritten in Python. All chart in project article is based on this data.

---
## Reproducibility
The code running the analysis is written in Python 3. it also requires BeautifulSoup and pandas．
BeautifulSoup for scraping, pandas for data loading and analysis. All works done on Jupyter notebook.
