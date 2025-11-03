# **🌐 InternMatch Pro**

**InternMatch Pro** is an intelligent, cloud-integrated internship recommendation system that analyzes resumes, extracts key technical skills, and matches users with the most relevant internships and crash courses.  
It uses **Natural Language Processing (NLP)**, **Machine Learning (ML)**, and **Streamlit** to deliver personalized recommendations for learners and job seekers.

---

## **🚀 Features**

- 📄 **Smart Resume Parsing** – Extracts technical skills from uploaded PDF resumes.  
- 🤖 **AI-Powered Skill Matching** – Compares user skills with domain skill sets using ML + NLP.  
- 💼 **Internship Recommendations** – Suggests domain-specific internships dynamically.  
- 🎓 **Crash Course Finder** – Recommends online learning resources for missing skills.  
- ☁️ **Firebase Integration (Optional)** – Stores user skill profiles securely on the cloud.  
- 📊 **Interactive Dashboard** – Built with Streamlit for an engaging user experience.  
- ⚡ **Dynamic UI** – Automatically updates missing and matching skills visually.  

---

## **🧩 Tech Stack**

| Layer | Technology Used | Purpose |
|--------|------------------|----------|
| **Frontend** | Streamlit | Web UI & Dashboard |
| **Backend** | Python | Core logic & APIs |
| **Database (Optional)** | Firebase Firestore | Cloud data storage |
| **Machine Learning** | scikit-learn, spaCy | Skill extraction & domain analysis |
| **Data Handling** | pandas | Resume data structuring |
| **Text Processing** | pdfplumber, re, difflib | Resume parsing & fuzzy matching |

---

## **⚙️ Prerequisites**

Before running the project, ensure you have the following installed:

| Requirement | Minimum Version | Purpose |
|--------------|------------------|----------|
| **Python** | 3.10+ | Required to execute the Streamlit app |
| **pip** | Latest | For installing dependencies |
| **Streamlit** | 1.35+ | For creating the interactive UI |
| **Code Editor** | VS Code / PyCharm | For development |
| **Browser** | Chrome / Edge | To open the app locally |


Have your owe ServiceAccountkey.json from google Firebase and
Have your own Github Token for verified access of the information from your profile

### **🌈 How It Works**

User uploads their resume.

The system extracts technical skills using NLP (spaCy).

Extracted skills are compared with domain skill sets using TF-IDF.

Displays results:

✅ Matching Skills

⚠️ Missing Skills

💼 Internship Recommendations

🎓 Crash Course Suggestions

stores skill profiles in Firebase Cloud.

### **▶️ How to Run the Project**

Run this command in your terminal:

    ```bash
    streamlit run internmatch_app.py
---

See the ouput in localhost

    ```bash
    http://localhost:8501

---
