#  AI Resume Analyzer  

A personal AI project that analyzes resumes using Natural Language Processing (NLP) and Machine Learning.  
It evaluates resumes based on job descriptions, skills, and experience, then provides detailed feedback and scores to help job seekers improve their chances.

---

##  Project Overview
The **AI Resume Analyzer** reads a candidate’s resume (PDF or text), extracts key information such as skills, education, and work experience, and compares it with a target job description.  
It then generates:
- A **compatibility score** between the resume and the job description  
- **Skill match percentage**  
- **Recommendations** for missing or weak skills  
- **ATS-friendly insights**  

---

##  Features
-  **Resume Parsing:** Extracts skills, experience, and education  
-  **Job Match Scoring:** Compares resume content with job requirements  
-  **Keyword Extraction:** Identifies high-impact words used in job posts  
-  **AI Feedback:** Suggests improvements using NLP models  
-  **Visualization:** Displays skill match and score summaries  

---

##  Tech Stack
| Component | Tools Used |
|------------|-------------|
| **Programming** | Python, Google Colab |
| **Libraries** | pandas, scikit-learn, nltk, spacy, transformers |
| **Modeling** | BERT / DistilBERT for text embeddings |
| **Deployment (optional)** | Streamlit / Hugging Face Spaces (future) |

---

## Folder Structure
AI-Resume-Analyzer/
│
├── resume_analyzer.ipynb # Main Colab notebook
├── sample_data/ # Example resumes & job descriptions
├── model/ # Trained or saved models (optional)
├── requirements.txt # Dependencies
└── README.md # Project documentation

---

##  How to Run in Google Colab
1. Open the notebook in Google Colab  
    [Run it in Colab](https://colab.research.google.com/)  
2. Upload a sample resume (`.pdf` or `.txt`)  
3. Paste the job description text  
4. Click **Run All** to generate scores and feedback
5. bug=True in launch()
* Running on public URL: https://452ec280a001cdf654.gradio.live

---

##  Future Improvements
- Add web interface with **Streamlit**  
- Create automated PDF reports  
- Expand dataset with more diverse resumes  
- Add multilingual support  

---

##  Example Output
| Feature | Example |
|----------|----------|
| **Resume Score** | 82 / 100 |
| **Skill Match** | 74% |
| **Missing Skills** | SQL, AWS |
| **AI Suggestion** | “Consider adding measurable outcomes in your experience section.” |

---

## Contributing
Pull requests and feedback are welcome!  
If you’d like to collaborate or extend this project, feel free to fork and build upon it.

---

##  Author
**Adyasha Jena**  
📧 ajena0657@gmail.com 
🔗 [LinkedIn](www.linkedin.com/in/adyasha-jena-90953a309) | [GitHub](https://github.com/AdyashaJena11)

---

 *If you like this project, don’t forget to star the repo!*  

