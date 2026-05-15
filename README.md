<!-- Banner: 1500x500. Place rendered banner at ./assets/banner.png before pushing. -->
<p align="center">
  <img src="./assets/banner.png" alt="Aman Pandey — AI Systems · Agentic AI · RAG · Production ML" width="100%" />
</p>

<h1 align="center">Aman Pandey</h1>
<p align="center"><b>AI Systems Engineer</b> &nbsp;·&nbsp; Agentic AI &nbsp;·&nbsp; RAG &nbsp;·&nbsp; Production ML</p>
<p align="center"><i>MS Data Science @ ASU &nbsp;·&nbsp; GPA 4.0/4.0 &nbsp;·&nbsp; 4+ years production ML &nbsp;·&nbsp; Tempe, AZ</i></p>
<p align="center">
  <a href="https://amanpandey.ai"><img src="https://img.shields.io/badge/website-amanpandey.ai-0a0a0a?style=flat-square&logo=safari&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/amanpandeyy"><img src="https://img.shields.io/badge/LinkedIn-amanpandeyy-0a66c2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:amanpandey.ds@gmail.com"><img src="https://img.shields.io/badge/email-amanpandey.ds@gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://x.com/aman_720"><img src="https://img.shields.io/badge/X-@aman__720-000000?style=flat-square&logo=x&logoColor=white"></a>
</p>

---

### About

MS Data Science, Analytics & Engineering at **Arizona State University** (GPA 4.0/4.0, Dec 2026) with **4+ years of production experience** building ML pipelines, NLP systems, and analytics platforms. I care about the boring parts — evaluation, latency, drift — as much as the models. Currently focused on agentic AI, retrieval-augmented generation, and robust deep learning.

### Currently

| Track       | What                                                                  |
| ----------- | --------------------------------------------------------------------- |
| Building    | Agentic RAG patterns with tool-use, query rewriting, and re-ranking   |
| Researching | Frequency-domain adversarial robustness in Vision Transformers        |
| Exploring   | LLM evaluation harnesses, long-context retrieval, MCP, structured outputs |
| Open to     | AI/ML Engineering internships — Summer 2026                           |

### Experience

**Software Engineer** — *My Next Film, New Delhi* &nbsp;·&nbsp; Apr 2023 – Dec 2024
- Engineered a multilingual NLP pipeline (**114 languages**) using seq2seq Transformers on AWS (EC2, S3, Lambda) with Google/Azure speech APIs — improved translation accuracy by **76%** and reduced manual review costs.
- Shipped a reviewer web app with automated task allocation — cut project cycle time by **41%**, lifted translation quality by **20%**, and automated **400+** Amazon Polly voice narrations matched to character profiles.

**Data Analyst** — *Youth Buzz, Noida* &nbsp;·&nbsp; Sep 2022 – Mar 2023
- Built churn-prediction models (logistic regression, **84% AUC**) on **50K+** customer records using Python + SQL; RFM clustering surfaced fee-driven attrition and informed a retention strategy that cut attrition **50%** in fee-sensitive cohorts within a quarter.
- Boosted Net Promoter Score by **+10** via an analytics-driven strategy; automated survey reporting with zero-shot NLP classification and Power BI dashboards for leadership.

**Software Developer** — *Invesca Technology, Noida* &nbsp;·&nbsp; Dec 2020 – Jul 2022
- Architected Celery/Redis distributed task queues processing **2M+ daily transactions** — reduced pipeline latency by **40%** and held **99.9% SLA** through 10× peak traffic windows.
- Built log-analytics dashboards and multithreaded Python services that lifted backend throughput by **35%**; automated anomaly-detection alerts to prevent overload incidents.

### Featured work

A handful of projects that show how I think about systems — research-to-production, generative-to-classical.

**FreqShield-ViT** — Frequency-domain adversarial defenses for Vision Transformers &nbsp;·&nbsp; [repo →](https://github.com/aman-720/freqshield-vit)
- *Stack*: PyTorch · DeiT-Small · torch-dct · PyWavelets · SLURM
- Investigation of feature-level frequency-domain regularization for adversarially-trained ViTs across four band-weighting configs and three frequency transforms. Documents a Siamese collapse failure mode and a threat-model-asymmetric robustness finding; reproducible pipeline + spectral diagnostics. *Paper in draft.*

**GlucoCast** — Generative diffusion framework for blood-glucose forecasting
- *Stack*: PyTorch · Conditional Diffusion · Time-series
- Conditional diffusion model generating privacy-preserving synthetic CGM data conditioned on meals, insulin, and activity. **Outperformed LSTM/CNN baselines by 18% RMSE** on the OhioT1DM dataset.

**FinFusion** — Deep learning for S&P 500 forecasting &nbsp;·&nbsp; [repo →](https://github.com/aman-720/sp500-tft-forecasting)
- *Stack*: PyTorch Lightning · pytorch-forecasting · ARIMAX / LSTM baselines
- Benchmarked ARIMAX, LSTM, and Temporal Fusion Transformer across **450+ experiments (11 phases)**. Discovered gradient collapse in financial TFT; weekly resampling achieves **59.1% directional accuracy** across 9-fold rolling evaluation (2016–2024).

**Pulse2Symphony** — Biosignal-conditioned music generation
- *Stack*: CNN-LSTM · Emotion-conditioned Transformer · REMI tokenization · Mobile (PPG)
- HRV features (SDNN, RMSSD, LF/HF ratio) extracted from smartphone-camera PPG → mood classified into Russell's valence-arousal space via CNN-LSTM → personalized instrumental MIDI generated by an emotion-conditioned Transformer decoder.

**Traitlytics** — LinkedIn personality predictor &nbsp;·&nbsp; [repo →](https://github.com/aman-720/Analysing-Personality-from-LinkedIn-Profile)
- *Stack*: BERT · RoBERTa · TF-IDF · FastAPI · Docker · AWS (EC2)
- NLP pipeline predicting Big-Five personality traits from LinkedIn profile text using BERT and RoBERTa with TF-IDF features. Deployed batch and real-time REST endpoints on AWS.

**BasketIQ** — Market basket analysis on 32.4M Instacart transactions &nbsp;·&nbsp; [repo →](https://github.com/aman-720/BasketIQ)
- *Stack*: Python · mlxtend (Apriori) · scikit-learn · Tableau
- Mined Apriori association rules and segmented users into 5 RFM-based clusters via K-Means. Interactive dashboard to drive targeted marketing and retention strategies.

### Tech stack

**🧠 Agentic AI & LLM Systems**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-6E40C9?style=flat-square)
![Anthropic Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-1F2937?style=flat-square)

**🤖 Deep Learning & NLP**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Lightning](https://img.shields.io/badge/PyTorch_Lightning-792EE5?style=flat-square&logo=lightning&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![BERT](https://img.shields.io/badge/BERT-009688?style=flat-square)
![RoBERTa](https://img.shields.io/badge/RoBERTa-D32F2F?style=flat-square)
![Diffusion](https://img.shields.io/badge/Diffusion_Models-7B1FA2?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

**📊 Data Science & ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**☁️ Cloud & MLOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**🗄 Data & Storage**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**📈 Analytics & BI**
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=looker&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)

---

<p align="center">
  Open to conversations about agentic systems, RAG evaluation, and robust ML — reach out via
  <a href="https://www.linkedin.com/in/amanpandeyy">LinkedIn</a> or
  <a href="mailto:amanpandey.ds@gmail.com">email</a>.
</p>
