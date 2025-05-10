# AI-Powered Resume Screener 📄🤖

This project uses NLP to automatically analyze resumes and match them to job descriptions based on **skills**, **experience**, and **education**. It ranks resumes based on their relevance to job descriptions.

## 📦 Contents
- Dataset: `data/job_descriptions.csv` (sample job descriptions)
- Jupyter Notebook: `resume_screener.ipynb`
- Requirements: `requirements.txt`

## 🚀 How to Run
1. Install required libraries:  
   `pip install -r requirements.txt`

2. Open the Jupyter notebook:  
   `resume_screener.ipynb`

3. Run the cells to process and rank the resume.

## 📊 Techniques Used:
- Text Preprocessing with **TF-IDF** and **Word2Vec**.
- Resume Matching using **Logistic Regression** for ranking.
- **PDF/Word parsing** for reading resumes.

## 📁 Dataset Info
- **job_descriptions.csv**: Contains job descriptions.
- **Resumes**: Can be uploaded in PDF or Word format for processing.

