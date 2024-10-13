# RecruitMatic

Welcome to RecruitMatic, an AI-powered recruitment tool that streamlines the hiring process by analyzing applicant data and providing tailored insights. This README will guide you on how to set up and use the application.

## Requirements

To run RecruitMatic, you need to have:

- Python 3.x installed on your machine.
- Your own OpenAI API key.

## Tech Stack

- **Python**: The primary programming language used for development.
- **Streamlit**: A framework for creating interactive web applications.
- **OpenAI API**: For advanced natural language processing capabilities.
- **pdfplumber**: For extracting text from PDF files.
- **python-docx**: For processing Word documents.
- **python-pptx**: For handling PowerPoint presentations.
- **openpyxl**: For working with Excel spreadsheets.
- **langchain**: For efficient text processing and document analysis.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd RecruitMatic
   ```

2. **Create Secrets File:**
   Store your OpenAI API key in the `.streamlit/secrets.toml` file. The file should be structured as follows:
   ```toml
   [general]
   OPENAI_API_KEY = "your_api_key_here"
   ```

3. **Install Dependencies:**
   Install all necessary dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application:**
   Launch the app using Streamlit:
   ```bash
   streamlit run app.py
   ```

## Using the App

- **Upload Resumes:** Easily upload resumes or applicant data in supported formats (PDF, Word, Excel, etc.) to analyze candidate qualifications.
- **Ask Specific Questions:** Enter job-related questions to receive tailored insights, such as asking about specific skills, experiences, or cultural fit.
- **Generate Shortlists:** Quickly receive a ranked list of candidates based on their qualifications, helping you focus on the most promising applicants.
- **Compare Candidates:** Use the app to compare candidates side by side based on their skills and experiences related to your job description.
- **Get Recommendations:** Ask the app for recommendations on potential interview questions based on the analyzed data, ensuring a thorough selection process.

## Additional Information

For any issues or questions, feel free to check the project's documentation or reach out to the team. Enjoy transforming your recruitment process with RecruitMatic!
