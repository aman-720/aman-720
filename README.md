<!-- Banner: 1500x500. Place rendered banner at ./assets/banner.png before pushing. -->
<p align="center">
  <img src="./assets/banner.png" alt="Aman Pandey — AI Systems · Agentic AI · RAG · Production ML" width="100%" />
</p>

<h1 align="center">Aman Pandey</h1>

<p align="center">
  <b>AI Systems Engineer</b> &nbsp;·&nbsp; Agentic AI &nbsp;·&nbsp; RAG &nbsp;·&nbsp; Production ML
</p>

<p align="center">
  <i>MS Data Science @ ASU &nbsp;·&nbsp; GPA 4.0/4.0 &nbsp;·&nbsp; 4+ years production ML &nbsp;·&nbsp; Tempe, AZ</i>
</p>

<p align="center">
  <a href="https://amanpandey.ai"><img src="https://img.shields.io/badge/Portfolio-0A0A0A?style=for-the-badge&logo=safari&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/amanpandeyy"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="./Aman_Pandey_Resume.pdf"><img src="https://img.shields.io/badge/Resume-1F2937?style=for-the-badge&logo=readthedocs&logoColor=white" /></a>
  <a href="mailto:amanpandey.ds@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://x.com/aman_720"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
</p>

<br/>

## 🧭 About

> Building AI systems that reason over messy, real-world knowledge — and the boring infrastructure that keeps them honest in production.

MS in Data Science, Analytics & Engineering at **Arizona State University** (GPA 4.0/4.0, Dec 2026), with **4+ years of production experience** shipping NLP pipelines, ML systems, and analytics platforms across SWE, data, and research roles. I care about the boring parts of AI work — evaluation, latency, drift, failure modes — as much as the model itself.

Right now I'm focused on **agentic AI**, **retrieval-augmented generation**, and **robust deep learning**. Open to internships and collaborations on systems that ship.

<br/>

## 🎯 Currently

*A snapshot of what I'm spending time on this quarter.*

| | Track            | Focus                                                                  |
|-|------------------|------------------------------------------------------------------------|
| 🛠 | **Building**    | Agentic RAG patterns — tool-use, query rewriting, and re-ranking       |
| 🔬 | **Researching** | Frequency-domain adversarial robustness in Vision Transformers         |
| 📖 | **Exploring**   | LLM evaluation harnesses, long-context retrieval, MCP, structured outputs |
| 🎯 | **Open to**     | AI/ML Engineering internships — Summer 2026 · *CPT eligible*           |

<br/>

## 💼 Experience

*Where I've shipped real systems with real users.*

### Software Engineer — *My Next Film*
📍 New Delhi, India &nbsp;·&nbsp; 🗓 Apr 2023 – Dec 2024

- Engineered a multilingual NLP pipeline supporting **114 languages** using seq2seq Transformers on AWS (EC2, S3, Lambda) with Google/Azure speech APIs — lifted translation accuracy by **76%** and cut manual review costs.
- Shipped a reviewer web app with automated task allocation — reduced project cycle time by **41%**, improved translation quality by **20%**, and automated **400+** Amazon Polly voice narrations matched to character profiles across markets.

### Data Analyst — *Youth Buzz*
📍 Noida, India &nbsp;·&nbsp; 🗓 Sep 2022 – Mar 2023

- Built churn-prediction models (logistic regression, **84% AUC**) on **50K+** customer records using Python and SQL; RFM clustering identified fee-driven attrition and informed a strategy that cut attrition **50%** in fee-sensitive cohorts within one quarter.
- Boosted Net Promoter Score by **+10** via an analytics-driven strategy; automated survey reporting with zero-shot NLP classification and Power BI dashboards for leadership.

### Software Developer — *Invesca Technology*
📍 Noida, India &nbsp;·&nbsp; 🗓 Dec 2020 – Jul 2022

- Architected Celery/Redis distributed task queues processing **2M+ daily transactions** — reduced pipeline latency by **40%** and held **99.9% SLA** across peak campaigns handling **10×** normal traffic.
- Built log-analytics dashboards and multithreaded Python services that lifted backend throughput by **35%**; automated anomaly-detection alerts to prevent overload incidents.

<br/>

## 🚀 Featured Work

*A handful of projects that show how I think about systems — research-to-production, generative-to-classical.*

### FreqShield-ViT &nbsp;·&nbsp; [Repo →](https://github.com/aman-720/freqshield-vit)
*Frequency-domain adversarial defenses for Vision Transformers.*

**Stack:** `PyTorch` · `DeiT-Small` · `torch-dct` · `PyWavelets` · `SLURM`

Investigation of feature-level frequency-domain regularization for adversarially-trained ViTs across four band-weighting configs and three frequency transforms (DCT, DFT, Haar wavelet). Documents a Siamese collapse failure mode and a threat-model-asymmetric robustness finding. Reproducible pipeline with depth-resolved spectral diagnostics, ablations, and patch-attack evaluation. *Paper in draft.*

---

### GlucoCast
*Generative diffusion framework for blood-glucose forecasting.*

**Stack:** `PyTorch` · `Conditional Diffusion` · `Time-series`

Conditional diffusion model generating privacy-preserving synthetic CGM data conditioned on meals, insulin, and physical activity. **Outperformed LSTM/CNN baselines by 18% RMSE** on the OhioT1DM benchmark.

---

### FinFusion &nbsp;·&nbsp; [Repo →](https://github.com/aman-720/sp500-tft-forecasting)
*Deep learning for S&P 500 return forecasting.*

**Stack:** `PyTorch Lightning` · `pytorch-forecasting` · `ARIMAX` · `LSTM`

Benchmarked ARIMAX, LSTM, and Temporal Fusion Transformer across **450+ experiments** spanning 11 phases. Discovered gradient collapse in financial TFT; weekly resampling achieves **59.1% directional accuracy** across 9-fold rolling evaluation (2016–2024).

---

### Pulse2Symphony
*Biosignal-conditioned music generation on mobile.*

**Stack:** `CNN-LSTM` · `Emotion-conditioned Transformer` · `REMI` · `PPG`

HRV features (SDNN, RMSSD, LF/HF ratio) extracted from smartphone-camera PPG → mood classified into Russell's valence-arousal space via CNN-LSTM → personalized instrumental MIDI generated by an emotion-conditioned Transformer decoder.

---

### Traitlytics &nbsp;·&nbsp; [Repo →](https://github.com/aman-720/Analysing-Personality-from-LinkedIn-Profile)
*Big-Five personality prediction from LinkedIn profile text.*

**Stack:** `BERT` · `RoBERTa` · `TF-IDF` · `FastAPI` · `Docker` · `AWS (EC2)`

NLP pipeline predicting Big-Five personality traits from LinkedIn profile text using BERT and RoBERTa with TF-IDF features. Deployed batch and real-time REST endpoints on AWS.

---

### BasketIQ &nbsp;·&nbsp; [Repo →](https://github.com/aman-720/BasketIQ)
*Market basket analysis on 32.4M Instacart transactions.*

**Stack:** `Python` · `mlxtend (Apriori)` · `scikit-learn` · `Tableau`

Mined Apriori association rules and segmented users into 5 RFM-based clusters via K-Means. Interactive dashboard to drive targeted marketing and retention strategies.

<br/>

## 🛠 Tech Stack

*The tools and frameworks I reach for, organized by what they do.*

#### 🧠 Agentic AI & LLM Systems
- **Frameworks:** ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![MCP](https://img.shields.io/badge/Model_Context_Protocol-6E40C9?style=flat-square)
- **APIs & Models:** ![Anthropic](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
- **Patterns:** ![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square) ![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-1F2937?style=flat-square) ![Tool Use](https://img.shields.io/badge/Tool_Use-1F2937?style=flat-square) ![Structured Outputs](https://img.shields.io/badge/Structured_Outputs-1F2937?style=flat-square)

#### 🦾 Deep Learning & NLP
- **Frameworks:** ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Lightning](https://img.shields.io/badge/PyTorch_Lightning-792EE5?style=flat-square&logo=lightning&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
- **Models:** ![BERT](https://img.shields.io/badge/BERT-009688?style=flat-square) ![RoBERTa](https://img.shields.io/badge/RoBERTa-D32F2F?style=flat-square) ![ViT/DeiT](https://img.shields.io/badge/ViT%2FDeiT-4B8BBE?style=flat-square) ![Diffusion](https://img.shields.io/badge/Diffusion_Models-7B1FA2?style=flat-square)
- **Hardware:** ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

#### 📊 Data Science & ML
- **Languages:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
- **Libraries:** ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
- **Big Data:** ![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

#### ☁️ Cloud & MLOps
- **Cloud:** ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
- **Containers & Orchestration:** ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
- **Serving & Queueing:** ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
- **CI/CD:** ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

#### 🗄 Data & Storage
- **Databases:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
- **Warehouses:** ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)

#### 📈 Analytics & BI
- **BI:** ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=looker&logoColor=white)
- **Plotting:** ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)

<br/>

## 💬 Let's connect

<p align="center">
  Open to conversations about <b>agentic systems</b>, <b>RAG evaluation</b>, and <b>robust ML</b>.<br/>
  If you're building at this intersection — or hiring for it — reach out.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/amanpandeyy"><b>LinkedIn</b></a>
  &nbsp;·&nbsp;
  <a href="mailto:amanpandey.ds@gmail.com"><b>Email</b></a>
  &nbsp;·&nbsp;
  <a href="https://amanpandey.ai"><b>Portfolio</b></a>
</p>
