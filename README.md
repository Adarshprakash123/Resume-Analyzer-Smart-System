# 📄 Smart ATS Resume Analyzer

An AI-powered web application that helps job seekers optimize their resumes to pass **Applicant Tracking Systems (ATS)** by analyzing alignment with job descriptions. This tool provides match scoring, keyword analysis, and personalized feedback using **Google's Generative AI (Gemini)** through a clean and interactive **Streamlit** interface.

---

## 💼 Problem Statement

In today’s competitive job market, resumes must pass through ATS filters before reaching recruiters. These systems scan for specific keywords and job-related content, often rejecting resumes that:

- Lack alignment with the job description  
- Miss key technical or role-specific terms  
- Use inconsistent formatting  

This project addresses those issues by providing **automated, intelligent resume analysis** and **personalized improvement suggestions** to improve interview success rates.

---

## 🌍 Business Use Cases

### 1. ✅ Resume Optimization for ATS  
Help job seekers align their resumes with job descriptions by identifying missing keywords.

### 2. 🧠 Personalized Resume Improvement  
Deliver detailed suggestions to enhance resume content, structure, and relevance.

### 3. 🕵️ Efficient Resume Evaluation  
Streamline the process for recruiters, hiring managers, or career counselors to assess resumes quickly.

### 4. 🎯 Enhancing Job Search Success  
Increase candidates' chances of passing ATS filters and getting shortlisted.

### 5. 🧑‍🏫 Scalable Support for Institutions  
Educational platforms and HR consultancies can offer this as a career readiness tool.

---

## ✨ Key Features

- 📊 **Resume–Job Description Match Score**  
  Calculates a percentage match to indicate resume relevance.

- 🔍 **Keyword Gap Identification**  
  Lists important keywords missing from the resume that are present in the job description.

- 📋 **Detailed Profile Summary**  
  Provides AI-generated strengths, weaknesses, and actionable improvement tips.

- 🖥️ **Streamlit-Powered UI**  
  Simple, clean, and user-friendly interface for seamless interaction.

---

## ⚙️ How It Works

1. **Upload Resume**  
   Upload your resume in **PDF format**.

2. **Paste Job Description**  
   Add the job description in the text area provided.

3. **Run Analysis**  
   The app extracts and analyzes the resume using **Generative AI (Gemini)** via a prompt-based system.

4. **Review Results**  
   - **✅ Match Score**: Quantifies how well the resume matches the job.
   - **🧩 Missing Keywords**: Displays terms to add for better ATS alignment.
   - **🧾 Profile Summary**: Gives feedback on how to improve tone, structure, and impact.

---

## 🔮 Future Enhancements

- 📂 **Support for DOCX & TXT Resumes**  
- 🌐 **Multilingual Resume Analysis**  
- 📊 **Analytics Dashboard**: Identify common resume gaps across users.  
- 🛠️ **Custom Feedback by Sector**: Tailor suggestions for tech, management, healthcare, etc.  
- 🔌 **Job Portal Integration**: Auto-fetch JDs from sites like LinkedIn or Naukri.  
- 🧑‍💻 **User Accounts**: Save resume history and track improvements.

---

## 🧰 Tech Stack

- **Frontend/UI**: Streamlit  
- **AI Backend**: Google Generative AI (Gemini)  
- **PDF Parsing**: `pdfminer` / `PyMuPDF`  
- **Environment Config**: python-dotenv  
- **Language**: Python 3.8+

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/smart-ats-resume-analyzer.git
   cd smart-ats-resume-analyzer
