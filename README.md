# SecondLife – AI-Powered Clinical Trial Matching Platform

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Healthcare](https://img.shields.io/badge/Domain-Healthcare-red)
![Status](https://img.shields.io/badge/Status-Deployed-success)

## Live Demo

🚀 Hugging Face Deployment:  
https://huggingface.co/spaces/MrNoOne07/second-life

---

## Project Overview

SecondLife is an AI-powered healthcare analytics platform that connects patients with suitable clinical trials using Machine Learning, predictive analytics, and healthcare data processing.

The platform automates patient-trial matching by analyzing patient demographics, medical conditions, medications, geographic information, and clinical eligibility criteria to recommend relevant clinical trials.

The goal of the project is to reduce manual screening time, improve enrollment efficiency, and help patients discover personalized clinical trial opportunities.

---

## Problem Statement

More than 80% of clinical trials fail to meet enrollment targets due to inefficient patient matching and lengthy manual screening processes.

Patients often struggle to identify relevant clinical trials, while hospitals and research organizations face delays, increased operational costs, and reduced trial efficiency.

SecondLife addresses this problem by building an AI-powered recommendation system capable of predicting patient eligibility and automating clinical trial matching workflows.

---

## Key Features

- AI-based clinical trial eligibility prediction
- Automated patient-trial matching engine
- Patient and hospital dual portal system
- Healthcare data preprocessing and ETL pipelines
- Machine Learning driven recommendation system
- REST API integration using Flask
- SQLite database integration
- Interactive web application interface
- Docker deployment support
- Hugging Face Spaces deployment

---

# Tech Stack

## Programming Languages
- Python
- SQL
- HTML
- CSS

---

## Backend Development
- Flask
- REST APIs
- Jinja Templates

---

## Data Engineering & Processing
- Pandas
- NumPy
- ETL Pipeline Development
- Data Cleaning
- Data Transformation
- Feature Engineering

---

## Machine Learning
- Scikit-learn
- Random Forest
- Logistic Regression
- Gradient Boosting
- Predictive Analytics
- Model Evaluation

---

## Frontend
- HTML
- CSS
- Bootstrap

---

## Database
- SQLite

---

## Deployment & Tools
- Docker
- Hugging Face Spaces
- Git
- GitHub
- VS Code

---

# Datasets Used

- ClinicalTrials.gov Dataset
- Synthea Synthetic Healthcare Dataset
- MIMIC-IV Healthcare Dataset

---

# Machine Learning Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Feature Engineering
4. Patient-Trial Compatibility Scoring
5. Model Training
6. Model Evaluation
7. Eligibility Prediction
8. Trial Recommendation

---

# Key Achievements

- Processed 228K+ synthetic patient records
- Analyzed 571K+ clinical trial records
- Engineered 17+ patient-trial compatibility features
- Achieved 91.68% F1-score
- Achieved 99.25% recall
- Built scalable ETL pipelines for healthcare analytics
- Developed an end-to-end healthcare recommendation platform
- Successfully deployed using Hugging Face Spaces

---

# Project Architecture

The system consists of:

- Data Processing Layer
- ETL Pipeline Layer
- Machine Learning Prediction Layer
- Flask Backend APIs
- Patient & Hospital Interfaces
- Database Layer

---

# Project Structure

```bash
SecondLife/
│
├── Architecture Diagrams/
│
├── HFdeploy/
│   ├── Dockerfile
│   ├── requirements.txt
│   └── deployment files
│
├── static/
│
├── templates/
│   ├── landing.html
│   ├── patient.html
│   └── hospital.html
│
├── app.py
├── database.py
├── pipeline.py
├── secondlife.db
├── .gitignore
└── README.md
