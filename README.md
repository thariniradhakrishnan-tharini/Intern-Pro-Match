# 🌐 InternMatch Pro

**InternMatch Pro** is an intelligent, cloud-integrated internship recommendation system that analyzes resumes, extracts key technical skills, and matches users with the most relevant internships and crash courses.  
It uses **Natural Language Processing (NLP)**, **Machine Learning**, and **Streamlit** to provide personalized insights for learners and job seekers.

---

## 🚀 Features

- 📄 **Smart Resume Parsing** – Extracts technical skills from uploaded PDF resumes.
- 🤖 **AI-Powered Skill Matching** – Compares user skills with domain skill sets using ML + NLP.
- 💼 **Internship Recommendations** – Suggests domain-specific internships dynamically.
- 🎓 **Crash Course Finder** – Recommends learning resources for missing skills.
- ☁️ **Firebase Integration (Optional)** – Stores user skill profiles securely on the cloud.
- 📊 **Interactive Dashboard** – Built with Streamlit for an engaging user experience.
- ⚡ **Dynamic UI** – Automatically updates missing and matching skills visually.

---

## 🧩 Tech Stack

| Layer | Technology Used | Purpose |
|--------|------------------|----------|
| **Frontend** | Streamlit | Web UI & Dashboard |
| **Backend** | Python | Core logic & APIs |
| **Database (Optional)** | Firebase Firestore | Cloud data storage |
| **Machine Learning** | scikit-learn, spaCy | Skill extraction & domain analysis |
| **Data Handling** | pandas | Resume data structuring |
| **Text Processing** | pdfplumber, re, difflib | Resume parsing & fuzzy matching |

---

## ⚙️ Prerequisites

Before running the project, ensure you have the following installed:

| Requirement | Minimum Version | Purpose |
|--------------|------------------|----------|
| **Python** | 3.10+ | Required to execute the Streamlit app |
| **pip** | Latest | For package installations |
| **Streamlit** | 1.35+ | For creating the interactive UI |
| **Code Editor** | VS Code / PyCharm | For development |
| **Browser** | Chrome / Edge | To open the app locally |

### 🧠 Install the NLP Model

Download the spaCy English model (only once):
```bash
python -m spacy download en_core_web_sm
