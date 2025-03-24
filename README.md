# AI-powered Resume Screening and Ranking System

## Project Overview
This project is an AI-powered Resume Screening and Ranking System built using Python and Streamlit. The system helps recruiters efficiently match candidate resumes with job descriptions based on relevance. It utilizes NLP techniques and machine learning models to rank resumes based on job requirements.

## Features
1. Upload multiple job descriptions in text, pdf, or docx format
2. Upload multiple candidate resumes in text, pdf, or docx format
3. Preprocess job descriptions and resumes using NLP techniques
4. Compute similarity scores between job descriptions and resumes using TFIDF and cosine similarity
5. Display the top ten ranked resumes for each job description

## Technologies Used
1. Python for backend processing
2. Streamlit for frontend UI
3. Sklearn for text vectorization and similarity measurement
4. Spacy for text preprocessing
5. NLTK for natural language processing
6. PyPDF2 and python-docx for extracting text from resumes and job descriptions

## Installation
1. Clone the repository using `git clone repository_url`
2. Navigate to the project directory using `cd project_directory`
3. Install the required dependencies using `pip install -r requirements.txt`
4. Run the application using `streamlit run airesume.py`

## How to Use
1. Open the application in a web browser
2. Select the Jobs section and upload job descriptions
3. Select the Candidates section and upload resumes
4. Select the Matching section to view ranked resumes for each job description

## Deployment
The project is deployed using Streamlit Cloud which allows easy access and sharing of the application.

## Future Enhancements
1. Improve NLP processing with advanced language models
2. Add support for additional file formats
3. Implement a database to store job descriptions and resumes
4. Introduce machine learning models for better resume ranking

This project is designed to streamline the recruitment process by automating resume screening and ranking based on job relevance.
