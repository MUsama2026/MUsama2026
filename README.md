# Hi, I'm Usama 👋

### Data scientist — I like the questions where the honest answer is "not quite"

I work mostly in SQL and Python, and what I enjoy is the part before the chart: deciding
what the data can actually support. In one project that meant telling the board their
headline claim didn't hold up. In another it meant refusing to declare a winner in an
A/B test, because two variants were statistically indistinguishable no matter how good
the raw number looked.

Right now I'm extending that foundation into machine learning and generative AI — the
same instinct applied to models rather than queries: knowing what a result can and
cannot be trusted to say.

- 🌍 Based in Essen, Germany
- 🌱 Finishing a WBS data science and AI bootcamp
- 🔭 Building toward ML and GenAI — currently working through IBM Generative AI professional Certificate
- 💬 Happy to talk about SQL, python, experimental design, database modelling, ML, or GenAI

---

## 🛠 Tech I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Also:** statistical testing (chi-square, A/B design), database normalisation, data cleaning pipelines, dashboard design

**Currently going deeper:** `machine learning` · `scikit-learn` · `LLMs` · `RAG` · `NLP` · `prompt engineering`

---

## 📊 Projects

### 🌎 [Brazil Market Entry Analysis](https://github.com/MUsama2026/brazil-market-entry-analysis)

*Should a premium tech retailer expand into Brazil through an existing marketplace partner?*

Analysed **99,441 orders** across two years of marketplace data to test two claims the
client cared about: is this a credible channel for high-end products, and is delivery
fast enough? Found the median tech transaction was R$48 against a premium catalogue,
and that delayed orders took ~31 days instead of ~11 — dropping the average review
score from 4.13 to 2.61. Recommended a regional pilot with delivery SLAs rather than
the full national launch that was on the table.

`SQL` · `MySQL` · `Tableau`

---

### 💸 [Discount Strategy Analysis](https://github.com/MUsama2026/discount-strategy-analysis)

*Is discounting quietly eating the company's revenue, as the board believes?*

Built a five-stage cleaning pipeline over **41,319 orders** — every step reproducible,
every excluded order logged — then tested the board's claim directly. **It didn't hold
up:** the drop they were worried about is explained by ordinary seasonality and an
incomplete final quarter. Recommended keeping discounts, but varying depth by category,
since sensitivity ranges from strong in Chargers & Cables to almost none in Storage.

`Python` · `pandas` · `seaborn` · `Tableau`

---

### 🧪 [A/B Testing: Experimental Design](https://github.com/MUsama2026/ab-testing-experimental-design)

*Which homepage call-to-action drives the most clicks — and can we actually prove it?*

A **2×2 factorial design** testing button colour and text independently and together,
across ~100,000 visitors over 14 days. Chi-square test with Bonferroni-corrected
pairwise comparisons. Red buttons performed significantly worse on every comparison —
but the two leading variants were **statistically indistinguishable** (p = 0.465), so
the honest answer was that there is no winner, despite one having the higher raw CTR.

`Python` · `statistics` · `hypothesis testing`

---

### 📚 [Private Library Management System](https://github.com/MUsama2026/lianes-library)

*Who has my books?*

A full application for a private book collection: a **3NF MySQL schema** of nine tables,
a data layer in SQLAlchemy, and a Streamlit interface with two modes — one for the owner,
one for friends who can browse and request books. Includes a rule-based chatbot that
answers from the database and runs with no API key, backed by 27 tests that pass with
MySQL switched off.

`MySQL` · `SQLAlchemy` · `Streamlit` · `Python`

---

## 📫 Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/dr-muhammad-usama-b3b909208)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:muhammadusamawakil@gmail.com)

Thanks for stopping by.
