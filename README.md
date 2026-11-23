<h1 align="center">Hey, I'm Deepanshu Sharma 👋</h1>
<p align="center">
  <b>AI/ML Developer · Generative AI & Agentic Systems · Greater Noida, India 🇮🇳</b><br/>
  Building LLM agents, RAG apps, real-time voice AI & deployed ML services · Open to AI/ML / GenAI roles
</p>

<p align="center">
  <a href="https://linkedin.com/in/deepanshu-sharma-a08ba7319">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:deepanshusharma0846@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/DeepanshuSharma1607">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## 🙋 About Me

- 🤖 Third-year B.Tech CSE student building production-oriented **AI/ML and Generative AI systems**: LLM agent orchestration, RAG, real-time voice AI, time-series forecasting and gradient-boosted modeling
- ☁️ Built **AegisCloud**, a predictive, LLM-governed autoscaler (PyTorch LSTM + LangGraph + Gemini) validated on 26,600+ simulated minute-level ticks
- 📞 Built a **real-time AI voice agent** that streams Exotel phone calls to Gemini Live over FastAPI WebSockets
- 🚀 Shipped a live **4-agent research assistant** (search → extraction → drafting → self-review) to AWS EC2
- 🎙️ Built a **RAG-based YouTube video assistant** using faster-whisper, LangChain, Mistral AI & ChromaDB
- 🏏 Built a **live IPL win-probability predictor** (XGBoost, 0.8956 ROC-AUC on held-out seasons)
- 🐦 Competing in **Kaggle BirdCLEF 2026**: audio classification across 234 bird species
- 🏆 Solved **500+ DSA problems** across coding platforms · 🥉 3rd place, Space Day Competition (2025)
- 🎓 B.Tech CSE @ **IILM University** · CGPA **8.5 / 10** · Expected May 2028
- 📚 Completed the **AICTE-EduSkills Siemens-supported Data Science Master Programme** (Apr–Jun 2026)
- 🧑‍🏫 Core Member, DSA Wing, NextGenXAI Club (mentoring 50+ students, running workshops & contests)
- 📫 **deepanshusharma0846@gmail.com**

---

## 🚀 Featured Projects

**[AegisCloud: Predictive, LLM-Governed Autoscaler](https://github.com/DeepanshuSharma1607/agentic-ai-cloud-allocator)**
Forecasts request load 10 minutes ahead with a PyTorch LSTM and scales 1–4 Docker replicas through a FastAPI gateway. A LangGraph controller adds scheduled and unusual-event Gemini reviews on top of a rule-based fast path and scaling guardrails (119 LLM decisions, 0 LLM errors). Validated on 26,600+ ticks and 813K+ requests: 0.27% error rate, 39 ms median latency, 141 req/s peak.
`PyTorch` `LangGraph` `Gemini API` `FastAPI` `Docker` `Streamlit`

**[Real-Time AI Voice Agent](https://github.com/DeepanshuSharma1607/voice-agent)**
Telephone assistant that streams Exotel Voicebot calls to Google Gemini Live over a FastAPI WebSocket endpoint, with bidirectional PCM16 streaming, sample-rate conversion, async per-call sessions, hang-up detection, end-call tool handling and per-call transcript persistence.
`FastAPI` `WebSockets` `Gemini Live API` `Exotel` `Asyncio`

**[IPL Live Win Probability Predictor](https://github.com/DeepanshuSharma1607/ipl-winner-pedictor)** · [Live app](https://live-ipl-win-predictor.streamlit.app/) · [API docs](https://ipl-winner-pedictor.onrender.com/docs)
Ball-by-ball second-innings win probability from 279K+ historical deliveries, with leakage-safe lagged features and a season-based temporal split (2008–2023 train, 2024–2026 test). XGBoost reached 0.8956 ROC-AUC and 0.4355 log loss; a weighted ensemble with Logistic Regression and CatBoost is served via FastAPI and Streamlit.
`XGBoost` `CatBoost` `Scikit-learn` `FastAPI` `Streamlit`

**[Interview Accelerator: Adaptive AI Mock Interview Platform](https://github.com/DeepanshuSharma1607/edxso/tree/main/ass_3)** · [Live app](https://interview-accelerator-ahhu.onrender.com) · [Demo video](https://drive.google.com/file/d/17mNoSwgSx_uwf1n0Ype2ps7raPVV0P3K/view?usp=drivesdk)
Takes a resume and job description, produces a job-fit analysis, then runs an adaptive interview state machine (screening, competency, deep-dive) with contextual follow-ups, speech recognition, text-to-speech and automated performance reports.
`FastAPI` `Gemini API` `faster-whisper` `Edge TTS` `Render`

**[EchoMind: AI-Powered YouTube Video Assistant](https://github.com/DeepanshuSharma1607/Ai-Powered-Video-Assistant)**
Full-stack RAG app that answers questions about any YouTube video: yt-dlp audio extraction, faster-whisper transcription, HuggingFace embeddings in ChromaDB, and a LangChain (LCEL) retrieval chain grounding Mistral AI answers, with persisted conversations. Containerized with Docker Compose and nginx.
`LangChain` `Mistral AI` `ChromaDB` `FastAPI` `Docker Compose`

**[AI-Powered Research Report Maker](https://github.com/DeepanshuSharma1607/Ai-Powered-Research-Report-Maker)**
Four-stage multi-agent pipeline (Tavily search agent, BeautifulSoup reader agent, Mistral writer chain, Mistral critic chain) that turns a single topic into a structured, self-reviewed research report in about 60 seconds. Deployed on AWS EC2 via Docker Compose.
`LangGraph` `Mistral` `Tavily` `FastAPI` `Streamlit` `AWS EC2`

**[BirdCLEF 2026: Kaggle Competition](https://github.com/DeepanshuSharma1607/BirdCLEF-2026)**
Mel-spectrogram pipeline (16 kHz mono, 5-second crops, 128 Mel bins) with augmentation over 35,549 recordings and 234 species. Fine-tuned a two-input EfficientNetB0 with a latitude/longitude/rating metadata branch that gates audio features, trained with focal loss on Kaggle GPUs.
`TensorFlow/Keras` `EfficientNetB0` `Librosa`

**[Real-Time Emotion Recognition System](https://github.com/DeepanshuSharma1607/emotion_recognizer)**
EfficientNetB4 classifier trained on about 47K facial images across five emotion classes (~80% validation accuracy), with a real-time webcam inference pipeline.
`TensorFlow/Keras` `EfficientNetB4` `OpenCV`

**[FastAPI Backend with PostgreSQL and Migrations](https://github.com/DeepanshuSharma1607/backend_proj)** *(in progress)*
Modular async REST backend with separate authentication, books and database layers, using SQLModel/SQLAlchemy over PostgreSQL via asyncpg, with Alembic migrations and Pydantic validation.
`FastAPI` `PostgreSQL` `SQLModel` `Alembic`

---

## 🛠️ Tech Stack

**GenAI & Agentic AI**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Mistral AI](https://img.shields.io/badge/Mistral%20AI-FA520F?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-4B0082?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**ML & Data Science**
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logo=python&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Backend & Deployment**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Languages & Tools**
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 📜 Certifications

- Model Context Protocol — Anthropic (Aug 2026)
- Agentic AI Foundation with LangGraph — LangChain (Aug 2026)
- Advanced Learning Algorithms — DeepLearning.AI & Stanford University (Mar 2026)
- Supervised Machine Learning: Regression & Classification — DeepLearning.AI & Stanford University (Feb 2026)

---

## 📊 GitHub Stats

<p align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=DeepanshuSharma1607&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DeepanshuSharma1607&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=DeepanshuSharma1607&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=DeepanshuSharma1607&label=Profile+Views&color=0e75b6&style=flat-square"/>
</p>
