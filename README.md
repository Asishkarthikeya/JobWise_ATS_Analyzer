# 🤖 JobWise – AI Resume Analyzer

Transform your resume into an interview-winning document with the power of AI.  
**JobWise** is a smart resume analysis system powered by **LLaMA 3** and **LangChain**, designed to help you stand out in job applications by optimizing your resume for ATS (Applicant Tracking Systems) and job relevance.

---

## ✨ Features

📄 **Resume Analyzer**  
Get match percentage, keyword insights, and improvement suggestions based on your job description.

🪄 **Magic Rephrasing**  
Reword resume lines using action verbs, impact phrases, and ATS-friendly formatting.

📊 **Skill Gap Analysis**  
Find missing skills in your resume compared to the job post and get tips to bridge the gap.

📁 **ATS Templates (Coming Soon)**  
Access clean, AI-suggested resume formats optimized for recruiter systems.

---

## 🚀 How to Use

1. **Set API Key**  
   Get your free Groq API key from [Groq Console](https://console.groq.com) and add it to your `.env` file:
   ```env
   GROQ_API_KEY=your_groq_api_key_here
Launch the App
git clone https://github.com/your-username/JobWise_ATS_Analyzer.git
cd JobWise_ATS_Analyzer
pip install -r requirements.txt
streamlit run app.py
Upload Your Resume & Job Description
The AI will analyze, rephrase, and compare for a perfect job fit.
📄 Supported File Formats

Resume: PDF (.pdf) and Word (.docx)
Job Description: Text input (paste it directly)
🧠 How It Works

JobWise uses a powerful AI agent based on LLaMA 3 (via Groq) and managed through LangChain to perform:

Resume parsing and formatting
Contextual comparison with job descriptions
Insight generation with match scores and keyword gaps
Rewriting and improvement suggestions
All processing is done instantly in your session – no data is stored.

🔧 Tech Stack

LLM: LLaMA 3 (via Groq API)
Agent Engine: LangChain
Frontend: Streamlit
Parsing: PyPDF2, python-docx
Env Management: python-dotenv
🌟 Perfect For

📌 Job Seekers
🧑‍💼 Professionals looking to switch careers
🎓 Students preparing their first resume
🧠 AI Enthusiasts building real-world projects
🛡️ Privacy & Security

No resume or job data is stored
All processing happens live in your browser session
API keys are securely handled via .env file
🎯 Get Started

Just upload your resume and paste a job description — JobWise will do the rest:

✅ Check match %
✅ Find missing keywords
✅ Suggest improvements
✅ Rephrase resume lines
✅ Optimize for ATS
