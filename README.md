# Hi there, I'm Sebastian! 👋

## 🤖 AI/ML Engineer | LLM Fine-tuning | RAG Architectures | MLOps

I build production-grade AI systems with documented system design, evaluation frameworks, and comprehensive MLOps pipelines. Specialized in **QLoRA fine-tuning**, **hybrid RAG architectures**, **model explainability**, and **cloud deployment**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/paul-sebastian-kradyel)
[![HuggingFace](https://img.shields.io/badge/🤗%20HuggingFace-Profile-yellow)](https://huggingface.co/KradyelSebi)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=flat&logo=gmail)](mailto:paulsebastiankradyel@gmail.com)

---

## 🚀 Featured Projects

### Enterprise HR RAG System ⭐
**Production RAG with Hybrid Retrieval + RAGAS Evaluation on AWS EC2**

- ✅ **Hybrid Retrieval**: BM25 sparse + FAISS dense + Reciprocal Rank Fusion (RRF)
- ✅ **RAGAS Evaluation Framework**: context_precision, faithfulness, answer_relevancy
- ✅ **Token-aware conversation memory** with automatic follow-up detection
- ✅ **Architecture Decision Records (ADRs)** + Mermaid system design diagrams
- ✅ Full MLOps: CI/CD (GitHub Actions), 72% test coverage, MLflow, Prometheus monitoring
- ⚡ **Stack:** AWS EC2, Docker, LangChain, FAISS, BM25, Groq Llama 3.3 70B, FastAPI

🔗 [Live Demo](https://advanced-ai-engineering-portfolio.onrender.com/) · [Repository](https://github.com/sebikradyel1-svg/Advanced-AI-Engineering-Portfolio/tree/main/GRADIO_RAG)

### Legal Text Generator 📝
**Phi-3-mini (3.8B) QLoRA Fine-tuning — Migrated from GPT-2**

- ✅ **10x model upgrade**: GPT-2 (355M) → Phi-3-mini (3.8B) via QLoRA 4-bit NF4
- ✅ Fits 3.8B model in **6.4GB VRAM** with double quantization on RTX 3060
- ✅ Only **2.44% trainable parameters** (r=32, alpha=64); loss 1.24 → 0.88
- ✅ **ADR-004** documents migration decision with alternatives analysis & VRAM budget
- ⚡ **Stack:** Phi-3-mini, QLoRA, BitsAndBytes, PEFT, HuggingFace Hub

🔗 [Live Demo](https://huggingface.co/spaces/KradyelSebi/legal-text-generator) · [Model Weights](https://huggingface.co/KradyelSebi/legal-text-phi3-lora) · [Repository](https://github.com/sebikradyel1-svg/Advanced-AI-Engineering-Portfolio/tree/main/legal-text-generator)

### Universal Image Classifier 🖼️
**VGG16 Transfer Learning + Grad-CAM Explainability**

- ✅ **95%+ accuracy** across 12 categories on 10,000+ images
- ✅ **Grad-CAM explainability**: visual heatmaps showing model attention regions
- ✅ Top-k class comparison for debugging misclassifications
- ⚡ **Stack:** TensorFlow, VGG16, Grad-CAM, OpenCV, Streamlit

🔗 [Live Demo](https://huggingface.co/spaces/KradyelSebi/animal-image-classifier) · [Repository](https://github.com/sebikradyel1-svg/Advanced-AI-Engineering-Portfolio/tree/main/image-classifier-project)

---

## 🏗️ System Design & Architecture

A key focus of my work is **engineering discipline beyond code**:

| Practice | Where Applied |
|----------|---------------|
| **Architecture Decision Records (ADRs)** | HR RAG, Legal Text Generator |
| **RAGAS Evaluation Framework** | HR RAG — systematic retrieval quality metrics |
| **Mermaid System Diagrams** | HR RAG data flow & component architecture |
| **Trade-off Analysis** | Phi-3 vs Mistral-7B vs Llama-3.2-3B |
| **VRAM Budget Planning** | QLoRA training on consumer hardware |
| **Evaluation-Driven Development** | RAGAS baseline → optimize → re-measure |

---

## 💼 What I Do

```python
class AIEngineer:
    def __init__(self):
        self.name = "Sebastian Kradyel"
        self.role = "AI/ML Engineer"
        self.location = "Resita, Romania 🇷🇴"
        
    def skills(self):
        return {
            "LLMs & GenAI": ["QLoRA/LoRA Fine-tuning", "Hybrid RAG (BM25+FAISS+RRF)", 
                             "RLHF/PPO", "RAGAS Evaluation", "Phi-3, Llama 3"],
            "System Design": ["ADRs", "Trade-off Analysis", "VRAM Budget Planning",
                             "Mermaid Diagrams", "Evaluation-Driven Development"],
            "MLOps": ["AWS EC2", "Docker", "CI/CD (GitHub Actions)", 
                     "pytest (72% coverage)", "MLflow", "Prometheus Monitoring"],
            "ML/DL": ["PyTorch", "TensorFlow", "Grad-CAM/XAI",
                     "Transfer Learning", "CNNs", "Transformers from scratch"],
            "Data": ["PostgreSQL", "FAISS", "BM25", "ChromaDB", 
                    "LangChain", "Pandas"]
        }
    
    def current_focus(self):
        return [
            "🔥 Hybrid retrieval architectures with evaluation frameworks",
            "⚡ QLoRA fine-tuning on consumer hardware (RTX 3060)",
            "📊 Model explainability (Grad-CAM, SHAP)",
            "🏗️ Documenting architectural decisions (ADRs)",
            "🚀 Seeking remote AI/ML contract roles"
        ]
```

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**MLOps & Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)

**AI/ML**

![HuggingFace](https://img.shields.io/badge/🤗%20HuggingFace-FFD21E?style=flat)
![LangChain](https://img.shields.io/badge/🦜%20LangChain-green?style=flat)
![FAISS](https://img.shields.io/badge/FAISS-blue?style=flat)
![Groq](https://img.shields.io/badge/Groq-black?style=flat)

---

## 🎓 Certifications

- 🏆 **IBM AI Engineering Professional Certificate** (13 courses) — 2025
- 🏆 **IBM Data Science Professional Certificate** (12 courses) — 2025
- 🏆 **AWS DevOps and AI Specialization** (3 courses) — 2026
- 🏆 **Machine Learning in Production (MLOps)** — DeepLearning.AI (Andrew Ng) — 2026
- 🎓 **Master of Science in Marketing** — Babes-Bolyai University (GPA: 9.54/10)

---

## 📈 Recent Activity

- 🔥 Built **hybrid retrieval** (BM25 + FAISS + RRF) for HR RAG system
- 📊 Implemented **RAGAS evaluation framework** with systematic quality metrics
- 🚀 Migrated Legal Text Generator to **Phi-3-mini (3.8B) via QLoRA 4-bit**
- 🔍 Added **Grad-CAM explainability** to Image Classifier
- 📝 Documented architecture decisions with **ADRs and Mermaid diagrams**
- ⚡ Set up **autodeploy to HuggingFace Spaces** via GitHub Actions

---

## 📫 Let's Connect!

I'm seeking **remote AI/ML contract or part-time roles** (20-30h/week). Specialized in:

- 🤖 **LLM Engineering** — QLoRA fine-tuning, RAG architectures, RLHF alignment
- 🏗️ **System Design** — ADRs, evaluation frameworks, trade-off analysis
- ⚙️ **MLOps** — AWS deployment, CI/CD, monitoring, Docker

**Open to roles:** LLM Engineer | AI Engineer | ML Engineer | MLOps Engineer | RAG Specialist

📧 **Email:** paulsebastiankradyel@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/paul-sebastian-kradyel) · 🤗 [HuggingFace](https://huggingface.co/KradyelSebi) · 📍 Resita, Romania (Remote worldwide)

---

⭐ **Star my repositories if you find them useful!**

