# Erin Weiss Portfolio

**Data Scientist and ML Engineer** · Designing, training, and deploying machine learning systems from research through production.

[![Portfolio](https://img.shields.io/badge/Portfolio-erin--weiss.github.io-blue?style=flat&logo=github)](https://erin-weiss.github.io/index.html)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-erinweiss3-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/erinweiss3/)
[![Email](https://img.shields.io/badge/Email-erin.michele.weiss%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:erin.michele.weiss@gmail.com)
[![Résumé](https://img.shields.io/badge/Résumé-Download_PDF-green?style=flat&logo=googledocs&logoColor=white)](https://drive.google.com/file/d/191c2Msghk1dNXZPXrVh-ex0RWGSA3HLl/view?usp=sharing)

---

## About

I build machine learning systems that go beyond the notebook. My recent work covers the full ML lifecycle: exploratory analysis, feature engineering, model comparison across multiple architectures, and production deployment with containerization, orchestration, monitoring, and CI/CD. I've trained models that predict within ~$1,300 of true market prices across 243k records and deployed them as production APIs with automated testing, health monitoring, and autoscaling infrastructure.

I'm equally comfortable deep in a feature importance analysis as I am writing Dockerfiles and Kubernetes manifests. I care about building models that are validated, documented, and ready to serve real traffic, not just ones that perform well in a notebook.

**Live portfolio →** [erin-weiss.github.io](https://erin-weiss.github.io/index.html)

---

## Featured Projects

### Used Car Price Prediction — Model Development

Predicts used-car listing prices within **~$1,300 at the median** across 243k vehicles, 29 manufacturers, and 5,600+ model variants. Compared three architectures, Ridge regression, CatBoost, and FT-Transformer (attention-based deep learning), with CatBoost selected for production based on its combination of accuracy, inference speed, and native categorical feature handling. Includes full EDA, feature engineering across 20+ vehicle attributes, and reproducible experiment management with versioned run artifacts.

**Tech:** `Python` · `scikit-learn` · `CatBoost` · `TensorFlow` · `Keras` · `keras-tuner` · `pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Quarto` · `joblib`  
**Links:** [Live Report](https://erin-weiss.github.io/used-car-price-prediction/notebooks/01_used_car_price_regression.html) · [GitHub Repo](https://github.com/Erin-Weiss/used-car-price-prediction) · [Portfolio Page](https://erin-weiss.github.io/articles/Used-Car-Price.html)

---

### Used Car Price Prediction API — Production Deployment

Takes the trained CatBoost model from Part 1 and deploys it as a **production-ready prediction service**. The API handles request validation with Pydantic v2, fuzzy matching of free-text user inputs, and median imputation of optional fields. Containerized with a multi-stage Docker build, orchestrated on Kubernetes with HPA autoscaling, and monitored via Prometheus + Grafana. Automated CI/CD through GitHub Actions runs the full test suite, including end-to-end predictions against the real model, on every merge to main.

**Tech:** `FastAPI` · `Uvicorn` · `CatBoost` · `Pydantic` · `Docker` · `Kubernetes` · `GitHub Actions` · `Prometheus` · `Grafana` · `pytest`  
**Links:** [Live Report](https://erin-weiss.github.io/used-car-price-api/) · [GitHub Repo](https://github.com/Erin-Weiss/used-car-price-api) · [Container Image (GHCR)](https://github.com/Erin-Weiss/used-car-price-api/pkgs/container/used-car-price-api) · [Portfolio Page](https://erin-weiss.github.io/articles/API-Used-Car-Price.html)

---

### Reinforcement Learning in Python

Implements reinforcement learning algorithms to optimize a mobile robot's path through a warehouse environment. Demonstrates exploration vs. exploitation trade-offs, policy optimization, hyperparameter tuning, and reward shaping through interactive code and visualizations.

**Tech:** `Python` · `NumPy` · `pandas` · `Matplotlib` · `Jupyter Notebook`  
**Links:** [Live Demo (Colab)](https://colab.research.google.com/drive/1AdGevMypjOROYdtjgmwzJGFNswwUC5mm?usp=sharing) · [GitHub Repo](https://github.com/Erin-Weiss/reinforcement-learning) · [Portfolio Page](https://erin-weiss.github.io/articles/RL-Article.html)

---

### Real Estate Analysis in R

Analyzes U.S. housing trends (2016–2022) using Realtor.com data. Explores how region, season, square footage, and market activity influence median listing prices. A multiple linear regression model explains **~95% of price variation**, supported by extensive visualizations.

**Tech:** `R` · `tidyverse` · `ggplot2` · `lubridate` · `summarytools` · `DT` · `ggpubr`  
**Links:** [Live Report](https://erin-weiss.github.io/R-Real-Estate-Project/) · [GitHub Repo](https://github.com/Erin-Weiss/R-Real-Estate-Project) · [Portfolio Page](https://erin-weiss.github.io/articles/Real-Estate.html)

---

### Excel Cleaning & Compare App

A deployed **Streamlit web application** for cleaning, standardizing, and comparing Excel files, built for real-world messy data from PDF-to-Excel invoice conversions. Supports flexible date parsing, forward/backward fill, multi-sheet output, and side-by-side dataset reconciliation. Includes a General App for broad use and an Aftermath App tailored to a specific client's recurring workflows.

**Tech:** `Python` · `Streamlit` · `pandas` · `openpyxl` · `Pillow` · `requests` · `email_validator`  
**Links:** [Live App](https://excel-cleaning-and-compare-app.streamlit.app/) · [GitHub Repo](https://github.com/Erin-Weiss/Excel-cleaning-and-compare-app) · [Portfolio Page](https://erin-weiss.github.io/articles/Excel-Cleaning.html)

---

### Michelin Stars in Washington, D.C.

An interactive **Tableau dashboard** exploring the Michelin-starred restaurant landscape in D.C. Compares the city's fine dining scene to global culinary hubs with interactive maps, cuisine filters, and custom UI design built in Figma with glassmorphism techniques.

**Tech:** `Tableau` · `Figma` · `HTML` · `CSS` · `Data Visualization Design`  
**Links:** [Live Demo](https://erin-weiss.github.io/tableau-DC-food-dashboard/) · [GitHub Repo](https://github.com/Erin-Weiss/tableau-DC-food-dashboard) · [Portfolio Page](https://erin-weiss.github.io/articles/Tableau-1.html)

---

<details>
  <summary><h2>📂 Additional Projects</h2></summary>

### Credit Analysis PCA

A **Principal Component Analysis** exploring financial and demographic patterns across 400 credit applicants. Reduces dimensionality to reveal underlying behavioral and financial drivers (Income, Credit Limit, Rating, Cards, Age, and Education) that distinguish applicant groups.

**Tech:** `R` · `tidyverse` · `Quarto` · `PCA` · `Data Visualization`  
**Links:** [Live Report](https://erin-weiss.github.io/PCA-Credit-Analysis/) · [GitHub Repo](https://github.com/Erin-Weiss/PCA-Credit-Analysis) · [Portfolio Page](https://erin-weiss.github.io/articles/credit-pca.html)

---

### States & Crime Clustering

An unsupervised learning analysis of the USArrests dataset, comparing **K-means clustering (k = 2–5)** and **hierarchical clustering** with and without scaling. Uses WCSS, the Elbow Method, and the Gap Statistic to identify natural crime-rate groupings across all 50 U.S. states, finding that **urbanization is not a consistent predictor of violent crime**.

**Tech:** `R` · `tidyverse` · `cluster` · `factoextra` · `K-means` · `Hierarchical Clustering` · `Quarto`  
**Links:** [Live Report](https://erin-weiss.github.io/Clustering-Analysis-US-Arrests/) · [GitHub Repo](https://github.com/Erin-Weiss/Clustering-Analysis-US-Arrests) · [Portfolio Page](https://erin-weiss.github.io/articles/clustering-project.html)

</details>

---

## Technical Skills

**ML & Modeling**  
`CatBoost` · `scikit-learn` · `TensorFlow` · `Keras` · `Deep Learning` · `Reinforcement Learning` · `NLP` · `Computer Vision` · `CNNs` · `PCA` · `K-means & Hierarchical Clustering` · `Recommender Systems` · `Time Series Analysis` · `Predictive Modeling` · `Feature Engineering` · `Hyperparameter Tuning` · `Optimization` · `Gurobi`

**MLOps & Deployment**  
`FastAPI` · `Docker` · `Kubernetes` · `GitHub Actions (CI/CD)` · `Prometheus` · `Grafana` · `Pydantic` · `Uvicorn` · `pytest`

**Data & Analysis**  
`Python` · `R` · `SQL` · `pandas` · `NumPy` · `PySpark` · `Apache Spark` · `Matplotlib` · `Seaborn` · `Jupyter` · `Quarto`

**Databases & Data Engineering**  
`PostgreSQL` · `MySQL` · `Microsoft SQL Server` · `SQLite` · `Hadoop` · `Google Cloud Dataproc` · `Data Warehousing` · `ETL` · `Alteryx` · `SSRS`

**Tools & Platforms**  
`Git` · `GitHub` · `Bash` · `Streamlit` · `Tableau` · `Google Analytics` · `Anaconda` · `LaTeX` · `Figma` · `HTML` · `CSS` · `JavaScript` · `Excel`

---

## Get in Touch

I love connecting with people who share a passion for data science, machine learning, and technology.  
Feel free to reach out through any of the platforms below:

- **LinkedIn:** [linkedin.com/in/erinweiss3](https://www.linkedin.com/in/erinweiss3/)
- **Email:** [erin.michele.weiss@gmail.com](mailto:erin.michele.weiss@gmail.com)
- **Portfolio:** [erin-weiss.github.io](https://erin-weiss.github.io/index.html)

---

Thank you for visiting my portfolio!  
I hope you find something that inspires you. 😊