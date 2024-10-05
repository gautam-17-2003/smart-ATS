# ATS Resume Expert

**ATS Resume Expert** is a web application built with **Streamlit** that analyzes and evaluates resumes against job descriptions using **Google's Gemini Pro Vision API**. This application leverages **Applicant Tracking System (ATS)** functionality to assess resumes and provide insightful feedback on alignment with job requirements, including strengths, weaknesses, and match percentages.

## Features

- **Upload PDF Resume:** The app allows users to upload resumes in PDF format.
- **Job Description Input:** Users can input the job description in a text box.
- **Resume Review:** The application provides a professional evaluation of the resume in terms of its alignment with the job description.
- **ATS Percentage Match:** The app evaluates the resume against the job description and provides:
  - A percentage match.
  - Missing keywords.
  - Final thoughts on the resume's suitability for the job.

## Installation

### Prerequisites

- Python 3.7+
- Install the required dependencies:

```bash
pip install -r requirements.txt
```
- Create a `.env` file in the root directory and add your Google Generative AI API key:

```bash
GOOGLE_API_KEY=your_google_api_key_here
```

- Run the Streamlit app:
```bash
streamlit run app.py
```

## Usage
1. Upload Resume: Upload a PDF resume using the file uploader.
2. Enter Job Description: Provide the job description in the text area.
3. Submit Request: Click on one of the following buttons to evaluate the resume:
* "Tell Me About the Resume": Get a professional evaluation of the resume based on the job description.
* "Percentage Match": Get a percentage match of how well the resume fits the job description, missing keywords, and final thoughts.

## Acknowledgments
* Thanks to Streamlit for the easy-to-use interface framework.
* Special thanks to Google's Gemini Pro Vision API for providing the advanced language model used in this project.

## Contact
For any inquiries or issues, please reach out to:

* Gautam
* pubrejagautam101@gmail.com
