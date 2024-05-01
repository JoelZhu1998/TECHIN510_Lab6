# TECHIN510_Lab6

Description: When writing resumes, we need to strive to align the content with the job description of the hiring company. However, different companies often have varying requirements and focal points for the same position, which can make resume revisions chaotic. The WeWantYou website can help you store job description information for different companies, analyze the match between your uploaded resume and the target position, and visualize the data. It also provides corresponding modification suggestions. Additionally, it stores information on your past resume versions and compares their fit to the target positions, helping you choose a specific version of your resume based on the situation.

User story: As a job seeker, I want the website to analyze the alignment between my uploaded resume and the job descriptions I am interested in, so that I can select the most suitable resume to submit for a particular job application.

Technology:
1. Google Gemini API
Function: Assists in analyzing the match between resumes and job descriptions and give suggestions.
2. Streamlit
Function: Serves as the front-end framework, allowing you to create interactive web interfaces where users can upload resumes, input job descriptions, and view matching results and suggestions.
3. Supabase
Function: Handles backend tasks like database management for storing user data and resumes, real-time updates, and automatic API generation.
