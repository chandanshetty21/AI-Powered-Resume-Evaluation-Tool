
# **AI-Powered Resume Evaluation Tool 📝**  

## **Overview**  
This project offers an AI-driven resume evaluation tool that assesses resumes against job descriptions. Using Google Gemini Pro with image processing, it evaluates how well a resume matches the job description and provides insights on strengths, weaknesses, and percentage match.

---

## **Features ⚡**  
- **Job Description Evaluation**: Provides a professional evaluation of resume alignment with job requirements.  
- **ATS Compatibility Check**: Analyzes resumes for compatibility with Applicant Tracking Systems (ATS).  
- **Resume-to-Job Match**: Calculates the percentage of match between resume and job description, highlighting missing keywords.

---

## **How It Works 🔄**  
1. **Resume Upload**: Users upload their resume in PDF format.  
2. **Job Description Input**: Users enter the job description to compare it with the resume.  
3. **AI Analysis**: The tool processes the resume using Google Gemini Pro and provides feedback on the resume's alignment with the job description, including a match percentage and keyword analysis.

---

## **Requirements 📦**  
1. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

2. Create a `.env` file and add your Google API key:  
   ```env
   GOOGLE_API_KEY=your_google_api_key
   ```

3. Run the app:  
   ```bash
   streamlit run app.py
   ```

4. Open the app at `http://localhost:8501`.

---

## **Usage 🧑‍💻**  
1. Input the job description in the provided text area.  
2. Upload your resume in PDF format.  
3. Click **"Tell Me About the Resume"** for a detailed evaluation or **"Percentage Match"** for a match score.  
4. View the evaluation and feedback provided by the AI.

---

## **Conclusion 📝**  
The AI-Powered Resume Evaluation Tool helps job seekers assess the effectiveness of their resumes in meeting job requirements and optimize their chances of passing ATS filters. It also provides feedback on areas to improve based on job description alignment.
