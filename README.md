
## CV Evaluation Tool 

This tool evaluates and matches candidate CVs against a job description using the power of OpenAI's GPT-4o, with a structured, explainable, and Excel-exportable scoring framework.


## 🔍 Overview

This tool automates the screening of CVs by:
- Extracting content from PDF resumes and a job description (JD)
- Structuring both CV and JD data into a consistent JSON format
- Using GPT to evaluate each candidate across 7 key dimensions
- Returning both **scores (0–10)** and **human-readable explanations**
- Exporting results to an Excel file for easy review and analysis

## Requirements

Install the following dependencies:

pip install openai pymupdf pandas openpyxl

If using Google Colab, packages will install automatically.

## 🔐 OpenAI Key
You'll need an OpenAI API key (GPT-4o or compatible).
You can set it in code using:

from getpass import getpass
api_key = getpass("Enter your OpenAI key:")

## How It Works
Upload Job Description (1 PDF)
Upload CVs (multiple PDF files)

## The tool:
Extracts text using PyMuPDF
Structures JD and CVs into JSON
Matches each CV to the JD across 7 evaluation dimensions:
Education
Work Experience
Skills
Certifications & Courses
Languages
Systems Knowledge
General Assessment

Outputs a score and explanation for each

Results saved to CV_Evaluation_Scorecard.xlsx

## Use Cases
- Shortlisting candidates
- Scoring applicants at scale
- Transparent hiring evaluations
- AI-based evaluation in HR Setups

## Note
This tool is for educational and demonstrative use.
It does not store any CV data and re-evaluates only what is uploaded.
Inspired by AI use cases in HR — not affiliated with any third-party tool.

## Credits
Developed by Abdullah Muslim

For queries or collaboration:
abdullahmuslim1412@gmail.com
