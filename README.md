# 🤖 LLM Uncertainty Quantification Cheat Sheet

This repository provides a compact and practical **cheat sheet** for understanding and applying **Uncertainty Quantification (UQ)** techniques in **Large Language Models (LLMs)**. It covers a wide range of scoring methods and provides a structured comparison between different approaches.

📄 **Download the PDF**: [LLM_Uncertainty.pdf](./LLM_Uncertainty.pdf)

---

## 📚 What’s Inside?

The cheat sheet summarizes the core methods for estimating confidence and detecting hallucinations in LLM outputs, categorized into three main groups:

### 🧠 1. White-Box Signals
- Token Entropy
- Log-Probability
- Cumulative Entropy
- Top-k Margin

### 🧪 2. Black-Box Signals
- EMR (Exact Match Rate)
- NCP (Non-Contradiction Probability)
- BLEURT / BERTScore / NSN
- Self-Consistency across samples

### 🧑‍⚖️ 3. LLM-as-a-Judge Scorers
- Reflexive Prompting
- Chain-of-Verification (CoVe)
- Retrieval-Augmented Self-Check

### 🔗 4. Hybrid UQ
- Combines white-box, black-box, and judge signals via a weighted ensemble
- Includes a **step-by-step example** on detecting a factual hallucination

---

## 🎯 Who is this for?

This cheat sheet is designed for:
- **AI researchers** working on hallucination detection, calibration, or LLM reliability
- **Developers** building trustworthy language model applications
- **Students & practitioners** looking for a concise reference to modern UQ techniques in NLP

---

## ✍️ Author

**Yukai Song**  
Ph.D. Student, Electrical and Computer Engineering  
University of Pittsburgh

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

