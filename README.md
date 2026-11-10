# Mickey Moore

**Python Software Engineer | AI/LLM Evaluation Infrastructure | Security & Data Pipelines**

Building zero-dependency Python CLI systems, LLM code-execution sandboxes, automated OWASP/SARIF security compliance gates, and leakage-safe machine learning pipelines on Linux.

---

### Featured Systems

- **[EvalForge: LLM Code Arena & AST Safety Sandbox](https://github.com/mickeywmoore/llm-code-arena)** [![CI](https://github.com/mickeywmoore/llm-code-arena/actions/workflows/ci.yml/badge.svg)](https://github.com/mickeywmoore/llm-code-arena/actions/workflows/ci.yml)
  Zero-dependency Python CLI (`evalforge`) benchmarking local (Ollama) and cloud LLM code generation via static Python AST security gating, isolated subprocess sandboxing, and RLHF/DPO preference JSONL export.
- **[SecPulse: API Security Posture & SARIF Compliance Gate](https://github.com/mickeywmoore/api-security-posture-auditor)** [![CI](https://github.com/mickeywmoore/api-security-posture-auditor/actions/workflows/ci.yml/badge.svg)](https://github.com/mickeywmoore/api-security-posture-auditor/actions/workflows/ci.yml)
  Zero-dependency Python CLI (`secpulse`) auditing HTTP/API security headers, CORS & cookie hardening, CI/CD `--fail-under` posture gates, and OASIS SARIF v2.1.0 telemetry.
- **[Retail-360: Customer Lifecycle & Neural LTV Engine](https://github.com/mickeywmoore/Retail-360-Customer-Lifecycle-Engine)** [![CI](https://github.com/mickeywmoore/Retail-360-Customer-Lifecycle-Engine/actions/workflows/ci.yml/badge.svg)](https://github.com/mickeywmoore/Retail-360-Customer-Lifecycle-Engine/actions/workflows/ci.yml)
  End-to-end Python CLI (`retail360`) transforming multi-table SQLite transaction logs via CTEs into an RFM feature store, K-Means persona segments, 90-day neural LTV forecasts, and regional MAE fairness audits.
- **[ChurnGuard: Telco Churn & Retention ROI Engine](https://github.com/mickeywmoore/customer-churn-prediction-model)** [![CI](https://github.com/mickeywmoore/customer-churn-prediction-model/actions/workflows/ci.yml/badge.svg)](https://github.com/mickeywmoore/customer-churn-prediction-model/actions/workflows/ci.yml)
  Leakage-safe Scikit-learn `ColumnTransformer` CLI (`churnguard`) benchmarking class-balanced Logistic Regression vs. Gradient Boosted Trees with probability threshold optimization for net campaign ROI.

---

### Technical Stack

- **Languages & Systems:** Python (3.10–3.14, `ast`, `subprocess`, `pyproject.toml`, `argparse` CLIs, Type Annotations), SQL (CTEs, Window Functions, SQLite), Bash
- **AI & LLM Infrastructure:** Local & Cloud LLM Inference Protocols (Ollama, OpenAI REST), Sandboxed Code Evaluation, RLHF / DPO Dataset Pipelines, Scikit-learn, TensorFlow / Keras, XGBoost
- **Security Engineering:** Python AST Static Analysis, OWASP HTTP/API Posture Auditing, OASIS SARIF v2.1.0, Web Application Security, Burp Suite
- **DevOps & Verification:** GitHub Actions CI/CD, Ephemeral Socket & Subprocess Integration Testing (`unittest` / `pytest`), Git, Linux (Debian / Kali)
