# Devashish Sharma — AI/ML & Software Engineer

[![Resume PDF](https://img.shields.io/badge/Download-Master_Resume_PDF-004B87?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/dhungababa/deva/main/Devashish_Sharma_AI_ML_Engineer_Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/devashish-sharma-a21787300)
[![GitHub](https://img.shields.io/badge/GitHub-dhungababa-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dhungababa)
[![Email](https://img.shields.io/badge/Email-devashishsharma719@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:devashishsharma719@gmail.com)

---

## Core Engineering Repositories

### 1. [UPI Fraud Detection & Defense SOC Engine](https://github.com/dhungababa/UPI_Fraud_Detection_SOC)
- **Tech Stack:** Python, XGBoost, SMOTE, FastAPI, SHAP, NetworkX, SQLite, Prometheus, Pytest
- **Architecture:** Trained SMOTE + XGBoost pipeline on 500K synthetic DPDP transactions (99:1 imbalance), achieving **76.4% test recall** with cost-sensitive loss thresholding. Includes stateful rolling-velocity feature store, spherical Haversine impossible-travel detection (`>800 km/h`), NetworkX mule-ring clustering, FastAPI inference + WebSocket streaming, sandbox-simulated ISO 8583 / FIDO2 SOAR payloads, and **11/11** passing Pytest integration checks.

### 2. [SEC Filings Intelligence & Forensic RAG Engine](https://github.com/dhungababa/SEC_Filings_RAG_Analyzer)
- **Tech Stack:** Python, FastAPI, FAISS, Sentence-Transformers, Ollama (Llama 3), Gemini API, pdfplumber, Plotly, Pytest
- **Architecture:** Hybrid semantic RAG microservice (`all-MiniLM-L6-v2` + FAISS) with live SEC EDGAR API (`data.sec.gov`) 10-K retrieval, CWE-22 path traversal sanitization, deterministic accounting distress models (Beneish 8-variable M-Score, Altman Z-Score, 5-factor DuPont ROE), regex numeric grounding checks, and **13/13** passing Pytest checks.

### 3. [Quantitative Equity Alpha & Risk Terminal](https://github.com/dhungababa/AI_Stock_Predictor_Quantitative)
- **Tech Stack:** Python, XGBoost, FinBERT, yfinance, Streamlit, Plotly, Pytest
- **Architecture:** Quantitative 5-year NSE research pipeline (22 Nifty equities, 1,206 trading days) combining 18 technical indicators with `ProsusAI/finbert` sentiment scoring, strict out-of-sample 5-fold `TimeSeriesSplit` validation (`0.48–0.56 ROC-AUC`), walk-forward backtests modeling `0.10% STT` and `Rs 20` brokerage, vectorized 1,000-path Monte Carlo GBM VaR/CVaR, synthetic 10-tier slippage simulator, and **9/9** passing unit tests.

---

## Master Resume Direct Download
- [Download Resume (PDF)](https://raw.githubusercontent.com/dhungababa/deva/main/Devashish_Sharma_AI_ML_Engineer_Resume.pdf)
- [Download Resume (DOCX)](https://raw.githubusercontent.com/dhungababa/deva/main/Devashish_Sharma_AI_ML_Engineer_Resume.docx)
