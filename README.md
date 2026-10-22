<h1 align="center">Gaspar Quintana</h1>

<p align="center">
  <b>Data Scientist · Machine Learning · AI Automation</b> · Córdoba, Argentina 🇦🇷<br/>
  <i>I build models that hold up on data they have never seen, and automations that remove manual work.</i>
</p>

<p align="center">
  <a href="mailto:gasparquintana125@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/GasparQC?tab=repositories"><img src="https://img.shields.io/badge/Projects-17-34d399?style=for-the-badge&logo=github&logoColor=white" alt="Projects" /></a>
</p>

---

## whoami

```python
class DataScientist:
    name = "Gaspar Quintana"
    location = "Córdoba, AR"
    education = "AI & Data Science, Universidad Siglo 21: 24/24 courses passed"
    certifications = ["AWS Certified Cloud Practitioner"]
    languages = ["es_AR", "en (B2/C1)"]

    def how_i_work(self):
        return "Baselines first, chronological splits for time series, and I report what fails too."
```

## What I'm building now

🎓 **Unbiased valuation estimates with ML (thesis).** Investors type 5-year assumptions into a spreadsheet by hand (sales growth, margins, FCF), and the verdict depends almost entirely on them. I'm building a model that gives a calibrated reference range for each assumption, based on what thousands of similar companies actually achieved. It uses point-in-time SEC data, quantile models (LightGBM, TabPFN, a custom network) with conformal calibration, walk-forward validation, and comparisons against random-walk, mean-reversion and base-rate baselines.

## Featured projects

| Project | What it does | Result |
|---|---|---|
| 🛰️ [**Land-cover classification with CNNs**](https://github.com/GasparQC/land-cover-cnn-eurosat) | CNN trained from scratch on Sentinel-2 imagery, across 11 controlled experiments | **91.7%** test · **91.3%** on 17,000 unseen images |
| 💣 [**RL agent for a minefield**](https://github.com/GasparQC/rl-minesweeper-agent) | Custom Gymnasium environment + DQN (Stable-Baselines3) | **100%** success vs. 7.1% random, 0 bombs hit |
| ✍️ [**Handwritten digits, to production**](https://github.com/GasparQC/mnist-handwritten-digits) | MLP vs. CNN grid, Wilson CI, production model, my own digits | **99.41%** test · 10/10 of my digits |
| 🎭 [**Agenda Cultural Córdoba bot**](https://github.com/GasparQC/agenda-cultural-cordoba-n8n) | n8n + Gemini agent over 17 real sources, voice and text, failure handling | 41 nodes · 4 failure modes handled |
| 📊 [**Deloto: spreadsheets to a data platform**](https://github.com/GasparQC/deloto-data-platform) | Real business: 4 years of Excel unified, profit model, leak found and fixed | R² **0.97 → 0.37** once honest |
| 💈 [**Killer Kutz booking system**](https://github.com/GasparQC/killer-kutz-booking) | Barbershop website, online booking, migration and automations | **553** customers migrated, 112 duplicates merged |

<details>
<summary><b>More projects</b></summary>

| Project | Highlight |
|---|---|
| [Breast cancer: SVM, DNN and PCA](https://github.com/GasparQC/breast-cancer-classification) | SVM 97.6% CV · 94.7% held-out test |
| [Heart disease: regularization vs. ensembles](https://github.com/GasparQC/heart-disease-ensemble) | L1 logistic regression 83.8% beats every ensemble |
| [Titanic, without leakage](https://github.com/GasparQC/titanic-random-forest) | 98.9% → 81.6% once I removed a target leak in my own work |
| [Natural-language peripherals search](https://github.com/GasparQC/peripherals-search-engine) | FastAPI · TF-IDF + rule-based ranking (team project) |
| [Statistical inference](https://github.com/GasparQC/statistical-inference) | Chi-square, ANOVA and mutual information with assumptions checked |
| [Neural network foundations](https://github.com/GasparQC/ml-foundations) | Perceptron and gradient descent in NumPy → tuned DNN |
| [Computer vision fundamentals](https://github.com/GasparQC/computer-vision-fundamentals) | OpenCV transforms, filters and a hand-built Sobel |
| [SQL Server sales forecasting](https://github.com/GasparQC/sql-sales-forecasting) | T-SQL stored procedure + Python forecast |
| [Power BI dashboards](https://github.com/GasparQC/powerbi-dashboards) | IT support and sales dashboards |
| [Buenos Aires real estate EDA](https://github.com/GasparQC/real-estate-eda-buenos-aires) | 146,660 listings cleaned and explored |
| [Blood pressure by age](https://github.com/GasparQC/blood-pressure-eda) | Messy clinical data made usable |

</details>

## Stack

**ML / AI**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Data & BI**
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

**Automation & tools**
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

## A bit more about me

```diff
+ Before data I sold cars and prefab houses, and worked as a journalist: I build tools thinking about who will use them
+ Automated weekly sales reporting from 4 hours to 30 minutes with n8n + Power BI
+ Replaced manual inventory tracking with a Telegram bot built with Claude Code (500+ items)
- Not a fan of 99% accuracy without a baseline: I've retracted two of my own after finding leaks
+ Open to Data Analyst / Data Scientist roles, full time
```

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=GasparQC&show_icons=true&hide_border=true&theme=tokyonight&count_private=true&include_all_commits=true" height="165" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GasparQC&layout=compact&hide_border=true&theme=tokyonight&langs_count=6" height="165" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=GasparQC&theme=tokyonight&hide_border=true" alt="Contribution streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GasparQC/GasparQC/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/GasparQC/GasparQC/output/github-snake.svg" alt="Contribution graph animation" />
  </picture>
</p>

<details>
<summary><b>🇦🇷 En español</b></summary>

Soy **científico de datos** de Córdoba. Tengo aprobadas las 24 materias de la Tecnicatura en IA y Ciencia de Datos (Universidad Siglo 21) y estoy haciendo mi tesis sobre estimaciones de valoración de empresas con ML.

Construyo modelos que se sostienen sobre datos que nunca vieron y automatizaciones que sacan trabajo manual. Siempre comparo contra una referencia simple, valido respetando el tiempo y cuento también lo que no funcionó.

Busco un puesto de **analista o científico de datos**, full time. 📫 gasparquintana125@gmail.com

</details>
