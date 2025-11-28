# Computational Analysis of Religious Inclusivity on Campus ( Will refine this readme file later for better context & will outline my thought process here )

---

## 1. Overview & Curiosity (The "Why NLP?")

This project serves as a practical application of **Natural Language Processing (NLP)** and data science techniques to validate complex social science phenomena. The core curiosity driving this research is: **Can unsupervised machine learning algorithms accurately identify and categorize complex human aspirations regarding tolerance, eliminating researcher bias?**

We applied this computational approach to student sentiment data regarding religious diversity and inclusivity within the highly pluralistic environment of **BINUS University Kemanggisan**.

## 2. Research Problem & Context

Indonesia, known for its high level of religious diversity, often faces structural challenges regarding the assurance of religious freedom. This research shifts the focus from macro-political issues to the micro-level: **the student experience**.

* **Problem Statement:** While campuses generally promote tolerance, the true level of comfort varies significantly among different religious groups (Majority vs. Minority). What are the specific systemic (facilities) and interpersonal (social) factors that truly determine a student's sense of belonging?

## 3. Methodology & Technical Approach

This project utilized a **Mixed Methods** approach, where two distinct datasets were generated and analyzed:

| Data Type | Method | Purpose |
| :--- | :--- | :--- |
| **Quantitative** (N=55) | Likert Scale Survey | Measure statistical averages (comfort index, facility satisfaction). |
| **Qualitative** (Open Text) | **NLP / LDA Topic Modeling** | Extract latent (hidden) thematic patterns from unstructured text data (student suggestions). |

### Computational Flow (The Core)

1.  **Preprocessing:** Python and NLTK were used to clean Indonesian text, remove complex stopwords, and tokenize the data.
2.  **Feature Engineering:** **TF-IDF Vectorization** was applied to weigh word importance.
3.  **Topic Modeling:** **Latent Dirichlet Allocation (LDA)** was executed to objectively group thousands of words into **5 core topics** of student aspiration.

## 4. Key Findings (The Results)
![test](/output1.png)

---
![test](/output2.png)

1. **To promote interfaith tolerance, students desire more interfaith interaction.**  
2. **Furthermore, students aspire to unique interfaith activities, such as religious comedy.**
