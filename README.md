<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0f2027,50:203a43,100:2c5364&text=B%20R%20Sathvik&fontColor=ffffff&fontSize=58&fontAlignY=38&desc=AI%20%2F%20ML%20Engineer&descSize=22&descAlignY=60&animation=fadeIn" width="100%" alt="B R Sathvik banner" />

<a href="https://github.com/sathvik-BR">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=720&height=45&lines=Computer+Vision+%C2%B7+Deep+Learning;NLP+%C2%B7+RAG+Pipelines;Explainable+AI+for+Healthcare;Building+end-to-end+AI+applications" alt="Typing animation" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/b-r-sathvik-a9b785328)
[![Portfolio](https://img.shields.io/badge/Portfolio-0f2027?style=for-the-badge&logo=githubpages&logoColor=00D9FF)](https://sathvik-br.github.io/sathvik-portfolio/)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/profile/sathvikbumisetty)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sathvikbumisetty@gmail.com)

<br/>

![Status](https://img.shields.io/badge/Status-Open_to_Work-2EA44F?style=flat-square)
![Roles](https://img.shields.io/badge/Roles-Fresher_AI%2FML_·_Internships-00D9FF?style=flat-square)
![Location](https://img.shields.io/badge/Location-Bengaluru_·_Remote-8A2BE2?style=flat-square)

</div>

---

## 👨‍💻 About Me

I'm a final-year **B.E. student in Artificial Intelligence & Machine Learning** at **AMC Engineering College, Bengaluru (VTU)**, building AI systems that go beyond notebooks: trained, explained, wrapped in APIs, and deployed.

My work sits at the intersection of **computer vision**, **deep learning**, and **LLM-powered retrieval (RAG)**, with a strong interest in **Explainable AI for healthcare**.

<table>
<tr>
<td width="50%" valign="top">

**🎓 Education**
B.E. in AI & ML · 2023 – 2027
AMC Engineering College · VTU
CGPA: **7.8**

</td>
<td width="50%" valign="top">

**🎯 Focus Areas**
Computer Vision · Deep Learning
NLP · RAG Pipelines · Explainable AI
Model Deployment & REST APIs

</td>
</tr>
</table>

---

## 🚀 Featured Projects

### 🫁 MediScan AI — Chest X-Ray Disease Detection
> **Explainable medical imaging + a RAG-powered Clinical Assistant**

A pneumonia detection system built on a fine-tuned **DenseNet-121**. Every prediction ships with a **Grad-CAM heatmap** showing which lung regions drove the decision, plus a **Clinical RAG Assistant** grounded in **WHO pneumonia guidelines**.

| 📊 AUC-ROC | 🎯 Test Accuracy | 🖼️ Training Images | 🧠 Backbone |
|:---:|:---:|:---:|:---:|
| **0.96+** | **90.2%** | **5,863** | **DenseNet-121** |

```mermaid
flowchart LR
    A[Chest X-Ray] --> B[DenseNet-121]
    B --> C{NORMAL / PNEUMONIA}
    B --> D[Grad-CAM Heatmap]
    C --> E[Clinical RAG Assistant]
    F[(WHO Guidelines<br/>FAISS Index)] --> E
    E --> G[LLaMA-3.3-70B via Groq]
    G --> H[Grounded Clinical Answer]
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![DenseNet-121](https://img.shields.io/badge/DenseNet--121-0f2027?style=flat-square)
![Grad-CAM](https://img.shields.io/badge/Grad--CAM-8A2BE2?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![LLaMA-3.3-70B](https://img.shields.io/badge/LLaMA--3.3--70B-0064E0?style=flat-square&logo=meta&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

[![Live Demo](https://img.shields.io/badge/🔴_Live_Demo-FF4B4B?style=for-the-badge)](https://mediscan-ai-jzmgxsbzhstdazbwtsmch6.streamlit.app/)
[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github)](https://github.com/sathvik-BR/mediscan-ai)

---

### 🗑️ Edge AI Camera System for Illegal Waste Dumping Detection
> **Real-time detection with a REST API backend and a live analytics dashboard**

- Real-time object detection pipeline using **YOLOv8** and **OpenCV**, running inference on live video streams
- **Flask REST API** backend with a live web dashboard powered by **Chart.js**
- **Flask-SocketIO** for real-time alert streaming, **SQLite** for structured incident logging
- Modular **MVC architecture**, unit tested with **pytest**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SocketIO](https://img.shields.io/badge/Flask--SocketIO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)

---

### 🧠 AI Knowledge Workspace — RAG + LLM
> **Chat with your PDFs using Retrieval-Augmented Generation**

Upload a PDF and query it in natural language. The app combines **semantic search** over vector embeddings with LLM generation, and adds **document summarisation** and **AI-generated flashcards** for studying.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![HuggingFace Embeddings](https://img.shields.io/badge/HF_Embeddings-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=flat-square)

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github)](https://github.com/sathvik-BR/ai-knowledge-workspace)

---

### 🎣 Ghost Fishing Gear Detection — YOLOv8
> **Computer vision for marine conservation**

Custom **YOLOv8** model trained on a **self-annotated marine dataset** to detect abandoned ghost fishing gear, reaching **70% validation accuracy**. Owned the full ML lifecycle independently: data collection, annotation, augmentation, training, inference optimisation, evaluation, and documentation.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github)](https://github.com/sathvik-BR/ghost-fishing-gear-detection-ml)

---

## 🛠️ Tech Stack

**🤖 AI / ML & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow_(Basic)-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**💬 NLP & RAG**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-8A2BE2?style=for-the-badge)

**⚙️ Backend, Data & Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_(Basic)-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**☁️ Cloud & Platforms**

![Oracle OCI](https://img.shields.io/badge/Oracle_OCI-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![HuggingFace Hub](https://img.shields.io/badge/HuggingFace_Hub-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Streamlit Cloud](https://img.shields.io/badge/Streamlit_Cloud-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle_GPU-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## 📜 Certifications

| Certification | Issuer | Year |
|:---|:---:|:---:|
| 🏅 Oracle Cloud Infrastructure 2025 — **AI Foundations** | Oracle | 2025 |
| 🏅 Oracle Cloud Infrastructure 2025 — **Generative AI** | Oracle | 2025 |
| 🏅 HackerRank Certified — **Python (Problem Solving)** | HackerRank | 2024 |

---

## 📊 GitHub Stats

<div align="center">

<img height="180" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=sathvik-BR&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f2027&title_color=00D9FF&icon_color=00D9FF&text_color=c9d1d9" />
<img height="180" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sathvik-BR&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f2027&title_color=00D9FF&text_color=c9d1d9" />

</div>

---

## 🌐 Languages

`English` · `Telugu` · `Hindi` · `Kannada`

---

<div align="center">

### 📫 Let's Build Something Together

*Open to fresher AI/ML roles and internships · Bengaluru / Remote*

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/b-r-sathvik-a9b785328)
[![Portfolio](https://img.shields.io/badge/View_Portfolio-0f2027?style=for-the-badge&logo=githubpages&logoColor=00D9FF)](https://sathvik-br.github.io/sathvik-portfolio/)
[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sathvikbumisetty@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:0f2027,50:203a43,100:2c5364&section=footer" width="100%" alt="footer" />

</div>
