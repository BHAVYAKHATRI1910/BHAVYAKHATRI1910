<div align="center">

<img src="https://raw.githubusercontent.com/BHAVYAKHATRI1910/BHAVYAKHATRI1910/main/assets/banner.svg" alt="Bhavya Khatri: AI/ML and GenAI engineer" width="100%"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-bhavya--khatri--ml-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/bhavya-khatri-ml/)
[![Email](https://img.shields.io/badge/Email-bhavyakhatri1910-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bhavyakhatri1910@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-visit_site-7C3AED?style=for-the-badge&logo=netlify&logoColor=white)](https://cool-starship-629a9c.netlify.app/)

![Open to work](https://img.shields.io/badge/status-open_to_AI%2FML_%26_GenAI_roles_2027-3fb950?style=flat-square)
![Location](https://img.shields.io/badge/based_in-Bhopal%2C_India-58a6ff?style=flat-square)

</div>

<br/>

## ⚡ The one-minute version

I build AI systems that have to work when the input is **live, messy and multilingual**: speech that needs captions in real time, plant data that needs explanations, resumes that keyword search can't understand.

> 🎓 Final-year B.Tech CSE (AI & ML) @ VIT Bhopal · 🏭 Internship at Hindustan Copper · 🏅 Google ML certified

<br/>

## 🔬 Watch a system work

**OmniMeet AI** captions and translates a video call as people speak, then a copilot turns the meeting into action items. This is the pipeline I own, and the dots are audio moving through it:

<div align="center">
<img src="https://raw.githubusercontent.com/BHAVYAKHATRI1910/BHAVYAKHATRI1910/main/assets/pipeline.svg" alt="OmniMeet AI pipeline: mic, VAD, Whisper, translation, subtitles, plus LLM copilot" width="100%"/>
</div>

<br/>

## 🧪 Projects (click to open)

<details>
<summary><b>🎙️ OmniMeet AI</b> &nbsp;·&nbsp; real-time multilingual meetings &nbsp;·&nbsp; <i>capstone, Group 98</i></summary>
<br/>

**What it does:** live subtitles in the viewer's language, plus an LLM copilot for summaries and action items.

**What I owned:** the AI services layer: voice activity detection, speech recognition and translation.

**Stack:** `FastAPI` `WebSockets` `WebRTC signaling` `Silero VAD` `Faster-Whisper` `CTranslate2` `NLLB-200` `MarianMT` `Gemini (optional copilot)`

**Design choices worth asking me about:**
- VAD before Whisper, so silence never reaches the model
- Fallback paths: energy-based VAD and a heuristic copilot if the primary models are unavailable

📄 Conference paper in progress · 🔗 [Repository](https://github.com/BHAVYAKHATRI1910/YOUR-OMNIMEET-REPO)

</details>

<details>
<summary><b>🏭 RecovAI</b> &nbsp;·&nbsp; explainable ML for a copper plant &nbsp;·&nbsp; <i>Hindustan Copper internship</i></summary>
<br/>

**What it does:** predicts process outcomes with XGBoost and explains them, so operators can see *why* a prediction moved.

**Built with a team** during my internship at Hindustan Copper (Malanjkhand).

**Stack:** `XGBoost` `SHAP` `FastAPI` `SQLite` `Streamlit` `anomaly detection` `drift monitoring` `LLM-generated reports`

**Design choices worth asking me about:**
- Why SHAP explanations matter more than one extra point of accuracy
- Monitoring for drift once real plant data starts changing

🔗 [Repository](https://github.com/BHAVYAKHATRI1910/YOUR-RECOVAI-REPO)

</details>

<details>
<summary><b>🧲 SkillSync AI</b> &nbsp;·&nbsp; semantic hiring platform</summary>
<br/>

**What it does:** matches candidates to roles by meaning, not just keywords.

**Stack:** `Spring AI` `pgvector` `Java` `PostgreSQL`

🔗 [Repository](https://github.com/BHAVYAKHATRI1910/YOUR-SKILLSYNC-REPO)

</details>

<details>
<summary><b>🌧️ RainCast AI</b> &nbsp;·&nbsp; next-day rainfall prediction &nbsp;·&nbsp; <i>SmartBridge × Google for Developers</i></summary>
<br/>

**What it does:** predicts whether it will rain tomorrow for agriculture use, served through a Flask web app.

**Stack:** `Python` `scikit-learn` `Flask` `Jupyter`

🔗 [Repository](https://github.com/BHAVYAKHATRI1910/Exploratory-Analysis-on-Rainfall)

</details>

<br/>

## 🧰 Toolbox

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-learning-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

</div>

<br/>

## 🎯 In progress

| | |
|:--|:--|
| ✅ | Real-time speech and translation pipeline |
| ✅ | Explainable ML in a plant-style setup |
| 🔨 | Deploying a project with a live demo link |
| 🔨 | AWS Solutions Architect Associate exam |
| 🔨 | Tests and CI on my main repos |

<br/>

## 💬 Ask me about

`Why VAD comes before Whisper` · `What SHAP changes for an operator` · `Streaming latency vs accuracy` · `What broke first on real plant data`

<br/>

<div align="center">

**Let's build something that runs.** &nbsp; [Say hi →](mailto:bhavyakhatri1910@gmail.com)

</div>
