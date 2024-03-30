

#ATS Resume Expert

This repository contains the source code for a Streamlit app acting as an ATS (Applicant Tracking System) for evaluating resumes against a given job description. The app uses the Google Generative AI (Gemini-pro-vision) model to analyze the resume and generate a response based on the provided prompts.

## Prerequisites
Before running the app locally, ensure that you have the following dependencies installed:

- streamlit
- google-cloud-generativeai
- dotenv
- base64
- pillow
- pdf2image
- io
Create a .env file with your Google API key:

Copy code
GOOGLE_API_KEY=<your_api_key>

How to use the app
## - Upload your resume (PDF): 
Upload a PDF file containing your resume in the designated file uploader. The app will display a confirmation message upon successful upload.

## - Enter the job description:
In the text area, enter the job description relevant to the resume you have uploaded.

## - Generate the evaluation:
Based on the prompts provided, the app will generate a professional evaluation of the resume with respect to the job description. Three buttons are available to generate different types of evaluations:

## - Tell me about my resume: 
This generates a general evaluation of the candidate's profile, highlighting their strengths and weaknesses according to the specified job requirements.

## - How can I improve my skills: 
This generates suggestions on how the candidate can improve their skills based on the job description.

## - Percentage match: 
This generates a percentage indicating the alignment of the candidate's profile with the job description, along with keywords that are missing from the resume and final thoughts.

## Running the app
To run the app locally, use the following command:

## Copy code
streamlit run app.py
The app will launch in your web browser. You can interact with the app by uploading a PDF file, entering the job description, and generating an evaluation based on your chosen prompt.



## Disclaimer
This project is for educational purposes and showcases the integration of Streamlit, Google Generative AI, and PDF parsing to evaluate resumes. The evaluations provided are AI-generated and should not be used as the sole basis for making hiring decisions.



