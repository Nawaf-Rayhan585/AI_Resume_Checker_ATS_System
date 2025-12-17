# 📁 AI Resume Analyzer (LLM-Based ATS System)

An AI-powered resume analyzer that works as a modern **ATS (Applicant Tracking System)** using Large Language Models (LLMs).  
It analyzes resumes against job descriptions, generates category-wise scores, gives a hiring verdict, and produces a **shareable resume score badge**.

---

## 🚀 Features

- 📄 PDF Resume Parsing (ATS-friendly)
- 🤖 Resume Comparing with Job Description Analysis
- 📊 Category-wise Scoring (out of 5)
  - Skills
  - Experience
  - Projects
  - Education
  - ATS Readability
- 🎯 Final Hiring Verdict
- ✅ Skill Matched Anylysis
- 🧠 AI Match Score with Animated Reveal
- 🏷️ Shareable Resume Score Badge (PNG)
- 📥 Downloadable AI Resume Report
- 🔄️ Key Points where to update the resume
- 📝 Key Points Why To Hire Or Reject The Person
- 🏗️ Checks CV structure
- 🔁 One-click Reset to Analyze Another Resume

---

## 🖥️ UI Preview

### Uploading Resume And Job Description
<img width="1919" height="715" alt="image" src="https://github.com/user-attachments/assets/5bf4811f-66b1-4b19-8cef-d06a59d3d0b9" />

<br/>

### Model Analysis
  - ATS Similarity Score
  - Final Verdict
  - Matched Skill Analysis
  - Shareable Score Badge
<br/>
<img width="1918" height="891" alt="image" src="https://github.com/user-attachments/assets/767fcef3-549d-4aec-9379-6540581e6689" />

  - Skills Analysis Explained
  - Projects Analysis Explained
  - Final Verdict With Logical Explanation
  - Points To Improve Resume
  - Resume Structure & ATS Readability Rating
  - Scan another resume
  - Download The Entire Report of The Resume
<br/>

<img width="1919" height="803" alt="image" src="https://github.com/user-attachments/assets/5a4ac024-f0c3-487e-8918-77adae4b43cd" />

<br/>

## ⚙️ How to Run the Project

- 📥 Clone the repository
- 🧪 (Optional) Create a virtual environment
- 📦 Install required dependencies
- 🔑 Add your Groq API key
- ▶️ Run the Streamlit app

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer
```

### 2️⃣ Create & Activate Virtual Environment (Recommended)
```bash
python -m venv venv
venv\Scripts\activate
```

> **Note:** On macOS/Linux, use `source venv/bin/activate` instead

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Environment Variables

Create a `.env` file in the project root:
```env
GROQ_API_KEY=your_groq_api_key_here
```

### 5️⃣ Run the Application
```bash
streamlit run main.py
```

### 6️⃣ Open in Browser

The app will automatically open in your default browser at:
```
http://localhost:8501
```

---
