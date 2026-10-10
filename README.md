<div align="center">

<a href="https://jeyadev.dev"><img src="https://jeyadev.dev/jeyadev-r.jpg" alt="Jeyadev R, AI/ML Engineer from Chennai, India" width="160" height="160" style="border-radius:50%"></a>

# Jeyadev R

**AI/ML Engineer · Full-Stack Developer · Applied Research**

B.Tech Artificial Intelligence & Data Analytics · Sri Ramachandra Institute of Higher Education and Research · 2024–2028

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/r-jeyadev)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jeyadev2006@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://jeyadev.dev)
[![Follow on GitHub](https://img.shields.io/github/followers/jeyadev-jd?label=Follow&style=flat-square&logo=github)](https://github.com/jeyadev-jd?tab=followers)

</div>

---

B.Tech student in AI and Data Analytics who learns by building. My work spans forecasting and risk models, computer vision, NLP and RAG, applied finance, and production full-stack SaaS. I prefer shipping a working version over polishing a slide.

Currently interning across two cleantech companies and serving as a Student Council Member at SRIHER.

---

## Tech Stack

**ML / AI**
`Python` `TensorFlow` `PyTorch` `XGBoost` `LightGBM` `CatBoost` `Scikit-learn` `Prophet` `FastAPI` `FAISS` `sentence-transformers` `llama.cpp`

**Full-Stack**
`React` `Next.js` `Node.js` `Express` `MongoDB` `PostgreSQL` `TypeScript` `Vite` `JWT`

**Infrastructure**
`Docker` `Cloudflare` `Vercel` `Wrangler` `Redis`

**CV / NLP**
`OpenCV` `YOLOv4` `Darknet` `TF-IDF` `ChemBERTa` `Grad-CAM`

---

## Projects

Full write-ups for every project: **[jeyadev.dev/projects](https://jeyadev.dev/projects)**

### AI / ML

| Project | What it is | Stack |
|---|---|---|
| [ScamShield](https://github.com/jeyadev-jd/ScamShield) | Explainable, obfuscation-robust scam SMS detector for Indian messages — 8 models benchmarked, deployed SVM hits 0.97 F1 | scikit-learn · PyTorch · DistilBERT · FastAPI · React |
| [PHYS-TRUST Lite](https://github.com/jeyadev-jd/phys-trust-lite) | Trust-adaptive, physics-informed air-quality estimation on one Arduino node with an LSTM-ensemble prior and conformal bands | Arduino · PyTorch · FastAPI · React · Ollama |
| [FRONTIER](https://github.com/jeyadev-jd/FRONTIER) | Local AI content agent for a student Discord community — drafts posts in your style, publishes only after human approval | FastAPI · React · Ollama · discord.py · MCP |
| [GloVe from Scratch](https://github.com/jeyadev-jd/glove-wikitext2) | GloVe word embeddings from first principles on WikiText-2 — hand-derived gradients, manual AdaGrad, no autograd | PyTorch · CUDA · NumPy |
| [sret-rag](https://github.com/jeyadev-jd/sret-rag) | Self-hosted RAG system on a 4-PC LAN cluster for my college — fully offline, no cloud | FastAPI · FAISS · llama.cpp · Qwen2.5 · SQLite |
| [PolyBot](https://github.com/jeyadev-jd/polybot-prediction-arbitrage) | Autonomous trading engine for Polymarket — live order book ingestion, strategy scoring, on-chain execution | Python · FastAPI · Web3 · Redis · PostgreSQL · Docker |
| [AbsorbAI](https://github.com/jeyadev-jd/AbsorbAI) | Clinical decision-support platform simulating drug behavior across ~45 drugs, with 10-layer PK/PD engine and Bayesian updates | Django · NetworkX · Gemma 1.5B |
| [Market Oracle](https://github.com/jeyadev-jd/market-oracle) | Commodity price forecasting via 9-model ensemble + Bayesian meta-ensemble | PyTorch · NeuralProphet · Chronos · Transformers |
| [AeroSight](https://github.com/jeyadev-jd/AeroSight) | AQI/mortality dual-model forecasting with auto-generated PDF reports — placed 2nd at Research Day 2025 | Prophet · XGBoost · Open-Meteo |
| [Cardio Detection Engine](https://github.com/jeyadev-jd/cardio-disease-detection-engine) | Cardiovascular risk dashboard + API backed by a model zoo with auto-selected best model | Streamlit · Flask · XGBoost · LightGBM · CatBoost |
| [Cardiovascular Risk Prediction](https://github.com/jeyadev-jd/cardiovascular-risk-prediction) | End-to-end ML pipeline with engineered features (BMI, MAP, pulse pressure, heuristic risk score) | scikit-learn · XGBoost · LightGBM · TensorFlow |
| [AI Drug-Food Interactions](https://github.com/jeyadev-jd/ai-drug-food-interactions) | Classifies drug-food interactions into 6 categories via TF-IDF + ensemble (99.2% accuracy) | Scikit-learn · Streamlit |
| [T20 Fantasy Impact Model](https://github.com/jeyadev-jd/t20-fantasy-impact-model) | Dual LightGBM models predicting batting/bowling impact for Dream11-style optimal XI selection | LightGBM · pandas · joblib |
| [Intel Scene Classification](https://github.com/jeyadev-jd/intel-scene-classification) | CNN vs VGG16 vs bagged ensemble comparison on 6 scene classes (~93% accuracy) with Grad-CAM | TensorFlow · Keras · scikit-learn |
| [ANPR-YOLOv4](https://github.com/jeyadev-jd/ANPR-YOLOv4) | Custom-trained YOLOv4 number plate detector for cars, bikes, and autos | YOLOv4 · Darknet · OpenCV |
| [EcoSynth](https://github.com/jeyadev-jd/Ecosynth) | Neuro-symbolic green retrosynthesis planner combining symbolic chemistry rules, RAG, and a green-chemistry scorer | FastAPI · ChromaDB · ChemBERTa · React |
| [HyperlocalAQ](https://github.com/jeyadev-jd/HyperlocalAQ) | High-res Chennai AQ modeling integrating 7 APIs with hybrid IDW and fire/traffic adjustments | Python · Folium |
| [Pollumap V3](https://github.com/jeyadev-jd/Pollumap-V3) | Real-time AQI dashboard with XGBoost 24h forecasts, A* healthy routing, and IoT sensor view | React · Flask · MongoDB · XGBoost · Leaflet |

### Full-Stack / SaaS

| Project | What it is | Stack |
|---|---|---|
| [Attendance ERP](https://github.com/jeyadev-jd/attendance-erp) | Multi-semester college attendance system built for real timetables — multi-hour labs, partial exam days, bunk detection | Next.js · Hono · Cloudflare Workers · D1 · Prisma |
| [ASPCV CRM](https://github.com/jeyadev-jd/aspcv-crm) | Full-stack CRM covering lead → deal → project → installation → support + HR, payroll, inventory, invoicing, and RBAC | React · TypeScript · Node.js · Express · PostgreSQL |
| [Aspiration Cleantech Ventures](https://aspcv.vercel.app/) | Production MERN-stack platform for a solar energy company — JWT auth, Helmet security, Cloudinary uploads | React · Vite · TypeScript · Node.js · MongoDB |
| [Aspiration Cleantech Academy](https://aspcvacademy.com/) | Job-oriented training platform (HVAC, entrepreneurship, digital marketing) deployed live on Cloudflare | Next.js · TypeScript · Express · MongoDB |
| [sret-noticeboard](https://github.com/jeyadev-jd/sret-noticeboard) | College notice board with admin panel, role-based auth, image notices, and FullCalendar event calendar | Node.js · Express · MongoDB · JWT · Multer |
| [VoteIQ](https://vote-iq-five.vercel.app/) | AI civic education app for first-time Indian voters — built in 8 hours at Google Prompt Wars | Flask · Gemini 2.0 Flash · Google OAuth |

### Tooling / Visualization

| Project | What it is | Stack |
|---|---|---|
| [Advanced CLI Web Scrapper](https://github.com/jeyadev-jd/Advanced-CLI-Web-Scrapper) | Full-site archiver handling dynamic pages, crawl depth, URL filtering, and concurrent downloads | Python · Playwright · BeautifulSoup |
| [Quantum Teleportation Simulation](https://jeyadev-jd.github.io/Quantum-Teleportation-Simulation/) | Zero-dependency browser visualizer for the quantum teleportation protocol with noise models | JavaScript · SVG |
| [Sudoku Visualisation](https://github.com/jeyadev-jd/Sudoku-Visualisation) | Side-by-side Backtracking vs MRV timing comparison with native graphics | C++ · SFML |
| [InstaAnalyzer](https://github.com/jeyadev-jd/InstaAnalyzer) | Identifies mutual followers and non-followbacks with clean terminal output | Python · Instaloader · Rich |
| [Arduino Calc: Matrix Edition](https://www.youtube.com/watch?v=08GiG0zbWGA) | Calculator mapping Von Neumann CPU concepts to Arduino hardware with a Web Serial matrix UI | Arduino · Web Serial API |
| [Urban Farming Simulator](https://github.com/jeyadev-jd/Urban-Farming-Simulator) | OOP rooftop farm sim modeling crop biology, seasonal weather, and market fluctuations | Java |
| [Crorepati Quiz Game](https://github.com/jeyadev-jd/Crorepati-A-CLI-Based-Quiz-Game-Using-Java) | CLI quiz game inspired by Kaun Banega Crorepati with lifelines and prize escalation | Java |

---

## Experience

**ASPCV CRM — SaaS Developer Intern** · Aspiration Cleantech Ventures · May 2026–Present

**Full-Stack Developer Intern** · Aspiration Cleantech Ventures · Jan–Mar 2026

**Digital Marketing Intern** · Aspiration Cleantech Academy · May 2026–Present

**Machine Learning Intern** · Sri Ramachandra Faculty of Engineering and Technology · May–Jul 2025

**Student Council Member** · SRIHER · Jul 2026–Present

---

<div align="center">

**31+ projects · 2 companies · Chennai, India · [jeyadev.dev](https://jeyadev.dev)**

If something here is useful, ⭐ the repo or follow for new projects.

</div>
