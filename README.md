# Student Aspirations on Religious Tolerance: An NLP Approach

## 📌 Project Overview
This repository contains the computational analysis code used for a mixed-methods research paper titled **"Student Comfort Levels in Expressing Religious Diversity at BINUS University."** This study was conducted for the **Character Building: Agama (Religion)** course. While the course is non-technical, this project leverages **Natural Language Processing (NLP)** to objectively analyze open-ended survey responses, bridging social science with data engineering.

## 🎯 Objective
The research aims to support **SDG 16 (Peace, Justice, and Strong Institutions)** by evaluating campus inclusivity. Instead of relying on manual interpretation of student aspirations which is prone to subjective bias this project uses **Latent Dirichlet Allocation (LDA)** to mathematically extract dominant themes from student feedback.

## ⚙️ Methodology
The analysis workflow in the Jupyter Notebook (`CB_Agama.ipynb`) involves:

1.  **Data Preprocessing**: 
    * Cleaning text (RegEx).
    * Tokenization (NLTK).
    * **Custom Stopword Removal**: Filtering out specific Indonesian conversational noise words (e.g., *'banget', 'intinya', 'terkait'*) to ensure high-quality topic extraction.
2.  **Exploratory Data Analysis**: 
    * Generating WordClouds to visualize high-frequency terms.
3.  **Topic Modeling**: 
    * Vectorizing text using **TF-IDF**.
    * Applying **LDA (Latent Dirichlet Allocation)** to cluster aspirations into coherent themes.

## 📊 Key Findings
The computational analysis revealed a shift in student needs from mere "availability" to **"quality of interaction."** The LDA model successfully identified three distinct aspiration patterns:

1.  **Interaction Dimension**: A desire for fluid, creative interfaith activities (comedy, competitions) rather than rigid seminars.
2.  **Infrastructure Dimension**: Viewing worship facilities as a support system and symbol of institutional equity.
3.  **Literacy Dimension**: The need for safe spaces for dialogue and education to reduce ignorance.

> **Note**: The quantitative side of this research (survey scores) indicated a high comfort index of **3.92/5.00**, confirming that while the tolerance climate is good, the *quality* of engagement can be improved.

## 🛠️ Tech Stack
* **Language**: Python
* **Data Processing**: Pandas, NumPy
* **NLP**: NLTK, Scikit-learn
* **Visualization**: Matplotlib, Seaborn, WordCloud

## 📂 Repository Contents
* `CB_Agama.ipynb`: The main notebook containing the NLP pipeline.
* `form_response.csv`: The raw dataset (anonymized) used for analysis.
* `Research_Paper.pdf`: The full research paper detailing background, methodology, and conclusion.

---
*This project demonstrates the application of Data Science techniques to solve real-world social problems.*
