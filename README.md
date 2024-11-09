# Resume Parsing and Job Recommendation System
This project is for resume parsing.
Welcome to the Resume Parsing and Job Recommendation System! This project is designed to seamlessly extract and analyze resume information and provide tailored job recommendations. Here’s an overview of the system:

Overview
The Resume Parsing and Job Recommendation System leverages machine learning and natural language processing (NLP) techniques to automate the process of extracting relevant information from resumes and recommending suitable job roles based on the extracted data. The system is built using Python and integrates with Streamlit to provide a user-friendly interface.

Key Features
Resume Parsing: Extracts text content from uploaded resume PDF files.

Information Extraction: Identifies and extracts key information such as name, contact details, email address, skills, education, and work experience.

Text Cleaning: Cleans and preprocesses the extracted text to remove unnecessary characters and standardize the content.

TF-IDF Vectorization: Converts the cleaned resume text into numerical vectors using the TF-IDF (Term Frequency-Inverse Document Frequency) technique.

Job Recommendation: Uses a pre-trained RandomForest Classifier to predict the most suitable job role based on the vectorized resume text.
