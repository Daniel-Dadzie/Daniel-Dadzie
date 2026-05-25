<div align="center">

# Daniel Yaw Dadzie

### Full Stack · Backend · ML Engineering
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://yourportfolio.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-yaw-dadzie)
 
[![Resume](https://img.shields.io/badge/Resume-4CAF50?style=for-the-badge&logo=googledrive&logoColor=white)](https://your-resume-link.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ddadzie120@gmail.com)

*Computer Science & Engineering · UMaT, Ghana*

</div>

---

## About Me

Growing up, I watched people around me — family, neighbours, students — navigate problems that technology could have made easier, but didn't. Not because the solutions were impossible, but because nobody had built them with those people in mind. That gap is what eventually drew me to software engineering, and it's what shapes how I think about it: systems should solve problems that actually matter to real people.


I'm a full stack and ML engineer focused on backend systems, API design, and end-to-end ML pipelines. I write clean, tested, production-oriented code and care deeply about what happens after the code ships — reliability, maintainability, and real-world performance.
I'm currently open to backend, full stack, and ML engineering internships and junior roles.

---

## Featured Projects


### Hostel Management System

A full-stack system for managing student accommodation at scale — room allocation, resident records, and access control across multiple user roles.

The interesting engineering problem here wasn't the CRUD layer — it was the **room allocation algorithm**: given a set of rooms with varying capacity, a pool of students with gender constraints and room preferences, and partial availability, allocate optimally. I implemented a constraint-satisfaction approach that runs greedily and falls back gracefully when no perfect match exists.

**Key engineering decisions:**
- RBAC across student, warden, and admin roles with Spring Security
- Normalised MySQL schema with indexing on high-frequency query paths (room availability, student lookup)
- Dockerised for consistent local and deployment environments
- REST API with structured validation and error contracts

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

🔗 [Repository](https://github.com/Daniel-Dadzie/hostel-management-system)

---

### NYC Taxi Trip Duration Predictor

A production-style ML system — not just a notebook, but a full inference service with experiment tracking, a serving layer, and a containerised deployment environment.

**Key engineering decisions:**
- XGBoost model with feature engineering on pickup hour, distance bins, and day-of-week patterns to reduce RMSE
- MLflow for experiment tracking — every run is reproducible, every model version is logged
- FastAPI inference endpoint with request validation
- Docker for environment consistency from local development to deployment

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logo=xgboost&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

🔗 [Repository](https://github.com/Daniel-Dadzie/nyc-taxi-ml)

---

### Breast Cancer Classification System

An end-to-end ML pipeline for binary cancer classification on the Wisconsin Breast Cancer dataset (569 samples, ~63% benign majority class).

A naive majority-class classifier would score ~63% accuracy by predicting "benign" every time. The goal was to meaningfully exceed that. I compared Logistic Regression and SVM with stratified k-fold cross-validation to prevent data leakage, achieving **97%+ accuracy** — a genuine ~34-point lift over baseline, not just a high number in isolation.

**Key engineering decisions:**
- Stratified k-fold splits to preserve class ratios across folds on an imbalanced dataset
- Model comparison framework: same preprocessing, same evaluation protocol, different algorithms
- Streamlit UI for real-time predictions from clinical feature inputs

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

🔗 [Repository](https://github.com/Daniel-Dadzie/breast-cancer-ml)

---

## Core Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**ML & Data**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=xgboost&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Infrastructure & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## Currently Working On

- Deploying the hostel management system
- Deploying the Taxi Duration Predictor to GCD with automated retraining
- First open-source contribution targeting a Python ML library

---

## GitHub Activity

<!-- <div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=Daniel-Dadzie&theme=github-dark-blue&hide_border=true)

</div> -->

---

## Engineering Philosophy

> Systems built for real people, in real conditions, with real constraints.

I approach projects with a systems mindset: API contracts before implementation, schema design before queries, reproducibility before model accuracy. I want to understand the failure modes before I write the first line.

Clean code matters. So does understanding why the system needs to exist.

---

<div align="center">

📧 [danielyawdadzie21@gmail.com](mailto:danielyawdadzie21@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/daniel-dadzie)

*Open to backend, full stack, and ML engineering internships & junior roles*

</div>
