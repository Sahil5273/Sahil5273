<h1 align="center">Hi there, I'm Sahil Kumar! 👋</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/sahilkumar"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://sahil-portfolio-76e8d.web.app/"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/Sahil5273"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<p align="center">
  <b>Full-Stack Software Engineer • AI Developer • Agentic Systems Builder</b>
</p>

I build **Agentic AI Systems**, **Robust RAG Pipelines**, and **Production-Grade Web Applications**. I specialize in creating reliable, high-performance systems with stateful guardrails, explainable decisions, and end-to-end deployment on cloud infrastructure.

---

## 🚀 Featured Projects

### 🩻 [RadScan-AI](https://github.com/Sahil5273/RadScan-AI) — Multimodal AI Radiology Triage & Report Copilot
*An autonomous radiology triage system that analyzes volumetric MRI scans to reduce radiologist burnout.*
* **Architecture:** 2.5D Volumetric CNN-BiGRU Neural Engine processing 24 parallel depth slices across Sagittal, Coronal, and Axial planes.
* **Explainability:** Grad-CAM visual heatmaps pinpointing lesion coordinates with an interactive 24-slice DICOM viewer.
* **Scale:** Trained on **819,100 DICOM slices (~530 GB)**; generates structured clinical reports in **< 3 seconds** via Vertex AI Gemini.
* **Infrastructure:** Scale-to-zero GCP Cloud Run with NVIDIA L4 GPU acceleration — **$0 idle costs**.
* **Tech Stack:** `Next.js 14` • `React 18` • `FastAPI` • `PyTorch` • `Vertex AI Gemini` • `GCP Cloud Run` • `Docker`

### 🏥 [X-CDS](https://github.com/Sahil5273/X-CDS) — Explainable Clinical Decision Support System
*An agentic, high-reliability clinical retrieval and validation pipeline for biomedical literature.*
* **Architecture:** Hybrid Retrieval (Dense ChromaDB + Sparse BM25) with Reciprocal Rank Fusion (RRF) and Cross-Encoder re-ranking.
* **Orchestration:** Stateful LangGraph self-correction loop decoupling generator (Gemini 3.5 Flash) and evaluator (Gemini 2.5 Pro) nodes to eliminate self-evaluation bias.
* **Metric highlights:** Achieved **93.37% factual accuracy (Ragas Faithfulness)** on clinical benchmarks via deterministic token-overlap alignment guardrails.
* **Tech Stack:** `Python` • `FastAPI` • `LangGraph` • `ChromaDB` • `Vertex AI` • `Docker` • `React`

### 👁️ [Marg-Darshak](https://github.com/Sahil5273/Marg-Darshak) — Edge AI Navigation Device
*An assistive computer vision system for visually impaired navigation, awarded **5th place at Health-Hack 2025** (VIT Bhopal × Johns Hopkins).*
* **Features:** Live video streaming from Raspberry Pi to a multi-threaded Flask server running YOLOv8 object detection, distance estimation at 15 FPS, and non-blocking Text-to-Speech voice alerts.
* **Tech Stack:** `Python` • `YOLOv8` • `OpenCV` • `Flask` • `Raspberry Pi`

### ✈️ [Smart-Travel-Agent](https://github.com/Sahil5273/Smart-Travel-Agent) — Autonomous Travel Planner
*A full-stack agentic itinerary optimizer featuring human-in-the-loop conflict resolution.*
* **Features:** Native Gemini tool-calling, structured JSON schema extraction, and parallel Firebase Cloud Functions executing itinerary modifications.
* **Tech Stack:** `React` • `Node.js` • `Firebase Cloud Functions` • `Gemini API` • `Firestore`

### 🥦 [ShareBite](https://github.com/Sahil5273/sharebite) — Food Redistribution Platform
*A surplus food donation matching platform with real-time role-based access control and AI metadata extraction.*
* **Features:** Integrated LocationIQ geocoding, Cloudinary image pipeline, and transaction-safe claims to prevent double-booking of food donations.
* **Tech Stack:** `React.js` • `Node.js` • `Express` • `Firebase Auth/DB` • `Gemini API`

---

## 💡 More Projects

| Project | Description | Tech |
|---------|-------------|------|
| ⌨️ [KeyForge AI](https://github.com/Sahil5273/keyforge-ai) | Full-stack multilingual typing speed test with AI-powered WPM prediction | `React` `TypeScript` `Firebase` |
| 📄 [Smart Document Assistant](https://github.com/Sahil5273/Smart-Document-Assistant) | AI-powered PDF Q&A using RAG with Gemini and LangChain | `Python` `Gemini API` `LangChain` |
| 🎙️ [Audio Transcription System](https://github.com/Sahil5273/Audio-Transcription-System) | Automatic speech-to-text transcription using OpenAI's Whisper | `JavaScript` `Whisper` |
| 🔒 [Privacy Filter CV](https://github.com/Sahil5273/Privacy-Filter-CV) | Real-time face detection and blurring for privacy protection | `Python` `OpenCV` |
| 🖼️ [BLIP2 Batch Captioner](https://github.com/Sahil5273/blip2-batch-captioner) | Batch image captioning with BLIP-2 | `Python` `Hugging Face` |
| 🏷️ [Image Caption Generator](https://github.com/Sahil5273/Image-to-Caption-Generator-using-Generative-AI) | Image labeling pipeline using Generative AI models | `Python` `Pillow` |
| 👗 [Vogue Vibe](https://github.com/Sahil5273/Vogue-Vibe) | Modern responsive website for a college fashion club | `HTML` `CSS` `JavaScript` |

---

## 🛠️ Tech Stack & Skills

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
    </td>
  </tr>
  <tr>
    <td><b>AI / ML / RAG</b></td>
    <td>
      <code>LangGraph</code> • <code>LangChain</code> • <code>PyTorch</code> • <code>Ragas</code> • <code>ChromaDB</code> • <code>OpenCV</code> • <code>YOLOv8</code> • <code>Gemini API</code> • <code>Vertex AI</code> • <code>Hugging Face</code> • <code>Whisper</code>
    </td>
  </tr>
  <tr>
    <td><b>Backend & DB</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
      <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
      <code>MongoDB</code> • <code>PostgreSQL</code> • <code>SQLite</code>
    </td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
    </td>
  </tr>
  <tr>
    <td><b>Cloud & DevOps</b></td>
    <td>
      <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white" alt="Google Cloud" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions" />
      <code>Cloud Run</code> • <code>NVIDIA GPU</code>
    </td>
  </tr>
</table>

---

## 📈 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sahil5273&show_icons=true&theme=tokyonight&hide_border=true" alt="Sahil's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sahil5273&layout=compact&theme=tokyonight&hide_border=true" alt="Sahil's Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sahil5273&theme=tokyonight&hide_border=true" alt="Sahil's Streak Stats" />
</p>

---

## 📫 Let's Connect!

<p align="center">
  <a href="https://sahil-portfolio-76e8d.web.app/">🌐 Portfolio</a> •
  <a href="https://www.linkedin.com/in/sahilkumar">💼 LinkedIn</a> •
  <a href="https://github.com/Sahil5273">🐙 GitHub</a>
</p>
