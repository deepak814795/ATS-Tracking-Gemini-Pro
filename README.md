# ATS Tracking System

## Overview

This is an Applicant Tracking System (ATS) tracking system developed using Gemini Pro, Python, and Streamlit. The system allows users to upload job descriptions along with their resumes. The app then provides insights into the resume, including the percentage match with the job description and suggestions for improving the match.

## Features

- **Resume Analysis:**
  - Users can upload their resumes and job descriptions.
  - The system analyzes the resume and provides a percentage match with the job description.
  - Suggestions are given on how users can improve the match to increase their chances of selection.

## Use Case

### Scenario:

1. **User uploads Resume and Job Description:**
   - Navigate to the web application and log in.
   - Upload their resume and the job description they are applying for.

2. **Resume Analysis:**
   - The system processes the resume and job description using Gemini Pro for natural language processing.
   - Provides a detailed analysis, including the percentage match between the resume and the job description.

3. **Suggestions for Improvement:**
   - The app offers suggestions on what users can include in their resume to increase the match percentage.
   - Recommendations may include specific skills, experiences, or keywords mentioned in the job description.

4. **User Takes Action:**
   - Users update their resume based on the suggestions.
   - Re-upload the modified resume to see the impact on the match percentage.

5. **Track Progress:**
   - Users can track the progress of their resume match percentage over time.
   - The system provides ongoing feedback on how well their resume aligns with job opportunities.

## Technologies Used

- [Gemini Pro](https://gemini.com/) - Used for natural language processing and conversational capabilities.
- [Python](https://www.python.org/) - Core programming language for backend development.
- [Streamlit](https://streamlit.io/) - Used for building interactive web applications with Python.

## Getting Started

### Prerequisites

- Python (version X.X.X)
- [Gemini Pro API Key](https://gemini.com/)
- Other dependencies (specified in requirements.txt)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ats-tracking-system.git
2. pip install -r requirements.txt
3. streamlit run app.py

