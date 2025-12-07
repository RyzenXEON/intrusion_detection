# 🛡️ Intrusion Detection System using XGBoost + LSTM  
**Hybrid ML approach for high-recall network threat detection**

This project implements an Intrusion Detection System (IDS) combining **XGBoost** for feature-level learning and **LSTM** for temporal anomaly detection.  
It aims to reliably identify malicious network behavior while minimizing false negatives, which is crucial for real-world cybersecurity.

This work was part of **peer-reviewed research published in IEEE CE2CT 2025**.

---

## 🚀 Key Outcomes

| Metric | Score |
|--------|------|
| Recall | **97.17%** |
| Accuracy | ~95% |
| False Negatives | Significantly reduced |

✔ Strong performance on detecting both known and unknown threats  
✔ Benchmarked for deployment feasibility  
✔ Designed for real network defenses  

---

## 🧠 Model Design

- **XGBoost** for feature extraction and anomaly cues  
- **LSTM** for sequence learning on traffic behavior  
- Combined architecture improves detection reliability significantly  

### Workflow Diagram
```mermaid
flowchart LR
A[Network Traffic] --> B[Preprocessing]
B --> C[XGBoost Feature Selection]
C --> D[LSTM Sequence Modeling]
D --> E[Threat Classification]
E --> F[Evaluation + Reports]
