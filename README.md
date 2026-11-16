# Danny McIntosh

<p align="center">
  <b>M.S. in Data Science @ Georgia State University</b> &bull; 
  <b>Enterprise AI, Knowledge Graphs & Clinical ML</b> &bull; 
  <b>Audio DSP Developer @ <a href="https://oceancoreinc.com">OceanCore Inc.</a></b>
</p>

<p align="center">
  <a href="https://github.com/dmcintosh5"><img src="https://img.shields.io/badge/GitHub-dmcintosh5-181717?style=flat&logo=github" alt="GitHub" /></a>
  <a href="https://oceancoreinc.com"><img src="https://img.shields.io/badge/Company-OceanCore%20Inc.-0078D7?style=flat&logo=safari" alt="OceanCore Inc." /></a>
  <a href="https://dmcintosh5.github.io"><img src="https://img.shields.io/badge/Portfolio-dmcintosh5.github.io-success?style=flat&logo=googlechrome" alt="Live Portfolio" /></a>
  <a href="mailto:dmcintosh5@student.gsu.edu"><img src="https://img.shields.io/badge/Email-dmcintosh5%40student.gsu.edu-EA4335?style=flat&logo=gmail" alt="Email" /></a>
</p>

---

## 🛠️ Technical Stack & Specialties

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-EB1000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white" />
  <img src="https://img.shields.io/badge/RDF%20%2F%20OWL%202-005A9C?style=for-the-badge&logo=w3c&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/JUCE%208-FF5500?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ModernGL-5.8-00C7B7?style=for-the-badge&logo=opengl&logoColor=white" />
</p>

---

## 🏛️ Featured Projects Portfolio (4 Pillars)

### 1. Audio Digital Signal Processing (DSP) & Creative Tech

| Project | Stack | Architecture & Key Quantitative Findings |
|---|---|---|
| [**`electric-ocean-dsp-plugin`**](https://github.com/dmcintosh5/electric-ocean-dsp-plugin) | `C++17`, `JUCE 8`, `VST3`, `AU` | Commercial multi-FX audio plugin featuring a 544-line custom C++ DSP processor: tempo-synced rhythm slicing (`1/128` to `2 Bars`), resonant aquaPhase filtering, chaos jitter LFO, FFT spectral scramble, ring-buffer freeze, and 50 automated XML presets. |
| [**`glitch-stutter-audio-engine`**](https://github.com/dmcintosh5/glitch-stutter-audio-engine) | `C++17`, `JUCE 8` | Real-time standalone audio engine utilizing an `AudioAppComponent` circular buffer for lock-free audio thread playback, audio slicing, and stochastic glitch/stutter loops. |
| [**`audio-reactive-3d-visualizer`**](https://github.com/dmcintosh5/audio-reactive-3d-visualizer) | `Python`, `Librosa`, `ModernGL`, `OpenGL 4.1` | High-performance GPU shader pipeline transforming real-time audio features (RMS amplitude, 120 BPM beat tracking, and spectral flux) into metallic 3D liquid mesh deformations and 1080p 60 FPS video renders. |

### 2. Ontology & Knowledge Engineering

| Project | Stack | Architecture & Key Quantitative Findings |
|---|---|---|
| [**`ppb-aurora-enterprise-knowledge-graph`**](https://github.com/dmcintosh5/ppb-aurora-enterprise-knowledge-graph) | `Python`, `Neo4j`, `LangGraph`, `Docker` | Enterprise Document-Driven Agentic Intelligence System (DAIS) mapping corporate HR policies into an OWL ontology (`ppb_hr_ontology.owl`), executing hybrid Cypher+vector multi-agent RAG with Streamlit UI. |
| [**`genai-query-languages-benchmark`**](https://github.com/dmcintosh5/genai-query-languages-benchmark) | `Python`, `RDFLib`, `Neo4j`, `SQL` | Comparative empirical benchmark analyzing LLM zero-shot and few-shot query synthesis across Relational SQL, Semantic RDF SPARQL, and Property Graph Cypher, measuring syntax error and hallucination rates. |

### 3. Machine Learning & LLM Systems

| Project | Stack | Architecture & Key Quantitative Findings |
|---|---|---|
| [**`transformer-distilbert-ordinal-rating`**](https://github.com/dmcintosh5/transformer-distilbert-ordinal-rating) | `PyTorch`, `Transformers`, `DistilBERT` | Fine-tuned DistilBERT on 50,000 unlabeled IMDB movie reviews to infer 1–5 star ordinal sentiment ratings when only binary ground truth exists, featuring 7-step EDA, ordinal loss modeling, and Quadratic Weighted Kappa evaluation. |
| [**`riverview-admissions-pipeline`**](https://github.com/dmcintosh5/riverview-admissions-pipeline) | `FastAPI`, `pgvector`, `PostgreSQL`, `Next.js 14` | Asynchronous admissions dossier processing pipeline with manifest validation gates, dual relational/vector storage (`pgvector`), LangChain summarizing agent, and Next.js review chat UI. |

### 4. Data Science & Predictive Analytics

| Project | Stack | Architecture & Key Quantitative Findings |
|---|---|---|
| [**`financial-analyst-eps-forecasting`**](https://github.com/dmcintosh5/financial-analyst-eps-forecasting) | `Python`, `Pandas`, `Scikit-Learn` | Exhaustive 57-step quantitative data science lifecycle auditing Wall Street analyst behavioral profiles, historical consensus estimates, and earnings-per-share (EPS) actuals across public equities. |
| [**`sci-clinical-cohort-analytics`**](https://github.com/dmcintosh5/sci-clinical-cohort-analytics) | `Python`, `Scikit-Learn`, `XGBoost`, `TreeSHAP` | Active clinical research on $N = 25,708$ NSCISC cohort: demonstrated a **4.9× employment multiplier for drivers**, identified a **$+3.38$ pt CHART Social Integration knot at age 28+**, and resolved diagnostic plateaus lifting **AUROC from 0.595 to 0.730** via hydrated longitudinal ML and TreeSHAP. |
| [**`time-series-forecasting-suite`**](https://github.com/dmcintosh5/time-series-forecasting-suite) | `Statsmodels`, `PMDArima`, `Pandas` | Econometric time-series forecasting suite featuring Brooklyn residential housing market analysis: monthly median transaction aggregation, ADF stationarity tests, and empirical comparison between ARIMA(1,1,1), seasonal SARIMA(1,1,1)x(1,1,1,12), and ETS (Holt-Winters). |

---

<p align="center">
  <sub>Danny McIntosh &bull; Built with precision across Data Science, Knowledge Engineering, and Audio DSP.</sub>
</p>
