# Resume Screening & Job Matching using NLP

- This project uses Natural Language Processing (NLP) and machine learning techniques to screen resumes and match them to job descriptions based on similarity scores.

## 📂 Project Overview

- Extract text from `.docx` resumes
- Clean and preprocess resume text
- Use TF-IDF vectorization to convert text to numeric features
- Calculate similarity using cosine similarity
- Rank and visualize top-matching resumes for each job description

## 📁 Dataset

- Source: [Kaggle Resume Dataset](https://www.kaggle.com/datasets/palaksood97/resume-dataset/discussion/174335)
- Format: `.docx` files converted to CSV for processing

## 🧠 Technologies Used

- Python (pandas, scikit-learn, nltk)
- NLP (tokenization, stopword removal, TF-IDF)
- Visualization (matplotlib, seaborn)

## 📊 Output

- `resumes_data.csv`: Raw resumes in CSV format
- `resume_similarity_results.csv`: All similarity scores
- `top_3_resumes_per_job.csv`: Top 3 matched resumes per job

## 📌 How It Works

1. Load and extract text from resumes
2. Clean text (lowercasing, punctuation removal, stopwords)
3. Apply TF-IDF vectorization
4. Measure similarity using cosine similarity
5. Output most relevant resumes for each job

## 🧠 Author

This project was built for learning NLP and showcasing resume/job matching using real-world data.

## Contact no: 6392579889 
## Name:  Ashutosh Pathak
