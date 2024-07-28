Here's the updated `README.md` file with the additional contact information:

```markdown
# Resume ATS for Hiring Manager

This project provides a Streamlit application that helps hiring managers improve resumes using an ATS (Applicant Tracking System) by evaluating resumes based on a given job description.

## Features

- Upload resume PDFs for evaluation
- Paste job descriptions for comparison
- Get a detailed evaluation including JD match percentage, missing keywords, and a profile summary

## Getting Started

### Prerequisites

- Python 3.7+
- Pip (Python package installer)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Mustafa-Shoukat1/Resume-ATS-for-Hiring-Manager.git
    cd Resume-ATS-for-Hiring-Manager
    ```

2. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the root directory of your project and add your Google API key:
    ```plaintext
    GOOGLE_API_KEY=your_google_api_key
    ```

### Usage

1. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Upload your resume PDF and paste the job description in the provided text area.

4. Click the "Submit" button to get the evaluation.

## Project Structure

- `app.py`: Main application script
- `requirements.txt`: Required Python libraries
- `.env`: Environment variables (Google API key)

## Example

Paste the job description in the provided text area and upload the resume PDF to get the evaluation.

```plaintext
Job Title: Generative AI (Gen AI) / ML Engineer / Data Scientist

Duration: Long term contract (Fully Remote)

Contract: W2

Job Requirement:
- Understanding of AI and Machine Learning (ML)
- Proficiency in Generative AI techniques, Vector DB, LLMs
- Experience with common open-source ML libraries, especially Python or R
- Knowledge of Deep Learning models for NLP
- Strong programming skills in languages such as Python and SQL
```
## Contact

Mustafa Shoukat
- GitHub: [Mustafa-Shoukat1](https://github.com/Mustafa-Shoukat1)
- Portfolio: [mustafashoukat.netlify.app](https://mustafashoukat.netlify.app/)
- Kaggler: [Mustafa Shoukat](https://www.kaggle.com/mustafashoukat)
- Email: mustafashoukat.email@gmail.com
```