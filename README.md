<div align="center">

<img src="./signature.svg" alt="A Random Forest model reveals that total_skill_count predicts job seniority about 8x better than any single skill" width="880"/>

</div>

<h1 align="center">Hi, I'm Arooba 👋</h1>
<h3 align="center">Data Analyst who turned her own job-hunt frustration into a self-updating dashboard</h3>

<p align="center">
I got tired of guessing what the job market actually wants from a fresher, so I built something that scrapes, stores, and analyzes it instead. Currently open to work, currently arguing with PostgreSQL about indexes.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/arooba-iftikhar-a7b794306/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/Aroobs-i"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

<br/>

## 📊 The receipts

<p align="center">
  <img src="https://img.shields.io/badge/Rows_Processed-1M+-ff2bd6?style=for-the-badge&labelColor=0a0014"/>
  <img src="https://img.shields.io/badge/Filtered_To-12.9K_relevant_roles-00fff5?style=for-the-badge&labelColor=0a0014"/>
  <br/>
  <img src="https://img.shields.io/badge/ML_Insight-skill_count_beats_skill_choice_8x-7b2ff7?style=for-the-badge&labelColor=0a0014"/>
  <img src="https://img.shields.io/badge/Pipeline-refreshes_daily,_zero_manual_steps-ffb347?style=for-the-badge&labelColor=0a0014"/>
</p>

> Trained a Random Forest to predict job seniority from posting data. Expected the usual suspects (Python, SQL, ML) to matter most. Instead found that **how many skills a posting lists** predicts seniority almost 8x better than **which specific skills** it lists — verified with two independent models before I trusted it enough to put it here.

<br/>

## 🛠️ What I actually use

<p align="center">
  <a href="https://www.postgresql.org/"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/></a>
  <a href="https://streamlit.io/"><img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/></a>
  <a href="https://scikit-learn.org/"><img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/></a>
  <a href="https://www.selenium.dev/"><img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/></a>
  <a href="https://www.tableau.com/"><img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/></a>
  <a href="https://www.microsoft.com/en-us/power-platform/products/power-bi"><img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/></a>
  <a href="https://www.microsoft.com/en-us/microsoft-365/excel"><img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/></a>
  <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/></a>
</p>

<br/>

## 🎓 Currently leveling up

<p align="center">
  <img src="https://img.shields.io/badge/Intro_to_Data_Science-in_progress-ff2bd6?style=for-the-badge&logo=googlescholar&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git_%26_GitHub-completed-00fff5?style=for-the-badge&logo=git&logoColor=black"/>
</p>

<br/>

## 🚀 Featured build: Data/Analytics Job Market Intelligence

<div align="center">

A self-updating platform comparing Pakistan's data/analytics job market against the global market. Live scraping → cloud PostgreSQL → SQL analysis → ML models → an auto-refreshing dashboard, with a daily scheduled job that writes straight to the cloud DB. No manual steps between "new posting goes live" and "dashboard shows it."

<p>
  <a href="https://data-jobs-market-intelligence-anbucscac4bdoy3sp47kwr.streamlit.app/"><img src="https://img.shields.io/badge/Live_Dashboard-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/></a>
  <a href="https://github.com/Aroobs-i/data-jobs-market-intelligence"><img src="https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

**Pakistan's market still leans on Excel and Power BI. The global market has already shifted to SQL, Python, and ML.**

| Skill | Pakistan | Global | Gap |
|---|---|---|---|
| Excel | **42.4%** | 10.6% | Pakistan 4x higher |
| Power BI | **36.4%** | 11.5% | Pakistan 3x higher |
| SQL | 15.2% | **42.7%** | Global 3x higher |
| Python | 15.2% | **37.0%** | Global 2.4x higher |
| Machine Learning | 9.1% | **21.2%** | Global 2.3x higher |

*% of each market's own postings mentioning the skill, normalized for fair comparison.*

Pakistan side is a live scrape of Rozee.pk that grows daily (58 postings and counting as I write this — small on purpose, since it's fresh data updating in real time, not a one-time dump). Global side is a 1.3M-row Kaggle LinkedIn dataset, filtered down to ~12,900 postings that are actually data/analytics roles, used as a benchmark rather than a Pakistan source.

Built the whole pipeline myself: a Selenium scraper that survives a JS-rendered site and rate limiting, a normalized PostgreSQL schema hosted on Neon, SQL analysis with window functions and self-joins, two ML models, and a dashboard that redeploys itself with zero manual steps every day.

</div>

<br/>

## 🔌 Connect

<p align="center">
  <a href="https://www.linkedin.com/in/arooba-iftikhar-a7b794306/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/Aroobs-i"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Aroobs-i&style=for-the-badge&color=ff2bd6&label=PROFILE+VIEWS" alt="Profile views"/>
</div>
