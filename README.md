Resume Analyzer 🚀

Overview
The Resume Analyzer is an AI-powered tool hosted on Hugging Face Spaces that analyzes resumes and matches them with job descriptions. This project leverages advanced machine learning models to extract insights from resumes and provide recommendations for improving candidate profiles.

Features

Resume Parsing: Extracts structured data such as skills, experience, and education.

Job Matching: Evaluates resumes against job descriptions to determine suitability.

Insights Generation: Provides actionable feedback to enhance resumes.

Interactive Interface: User-friendly web application hosted on Hugging Face Spaces.

Tech Stack

Framework: Streamlit

Hosting: Hugging Face Spaces

Language: Python

Libraries:


pandas for data manipulation

numpy for numerical operations

sklearn for machine learning tasks

streamlit for building interactive web applications

Installation and Setup (Local Development)

1. Clone the Repository
bash
git clone https://huggingface.co/spaces/PrasadPatil405/Resume_analyzer.git
cd Resume_analyzer
2. Install Dependencies
bash
pip install -r requirements.txt
3. Run the Application Locally
bash
streamlit run app.py
Access the app at http://localhost:8501.

Usage

Upload a resume in supported formats (PDF, DOCX).

Provide a job description for comparison.

Click "Analyze" to view:

Match score between the resume and job description.

Missing skills or keywords.

Recommendations for improvement.

Project Structure

text
Resume_analyzer/
├── app.py                 # Main application file
├── requirements.txt       # List of dependencies
├── README.md              # Documentation file
├── utils/
│   ├── resume_parser.py   # Resume parsing logic
│   ├── job_matcher.py     # Job description matching logic
│   └── helpers.py         # Utility functions
└── assets/
    ├── sample_resume.pdf  # Sample resume for testing
    └── sample_job_desc.txt # Sample job description for testing
Deployment

This project is deployed on Hugging Face Spaces. You can access it here.

Contribution

Contributions are welcome! Follow these steps:

Fork the repository.


Create a new branch (git checkout -b feature-name).

Commit your changes (git commit -m "Add feature").

Push to your branch (git push origin feature-name).

Open a pull request.
