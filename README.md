# AI Resume Matcher

This Streamlit app allows recruiters to upload resumes and match them against a job description using AI.
It ranks candidates using semantic similarity and GPT-based insights.

## Features
- Upload resumes (PDF & DOCX)
- Paste job descriptions
- AI-powered match scoring
- GPT-generated match explanations
- Filter candidates by match score
- Export matched candidates to CSV

## Setup
1. Add your OpenAI API key to `.streamlit/secrets.toml`
2. Install requirements: `pip install -r requirements.txt`
3. Run: `streamlit run app.py`
