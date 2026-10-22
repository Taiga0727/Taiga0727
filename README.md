<h1 align="center">Atilak Modetad</h1>

<p align="center">
  Applied Computer Science student at KMUTT<br>
  Computer vision · 3D point clouds · applied machine learning
</p>

<p align="center">
  <a href="https://atilak-resume.vercel.app"><b>Portfolio</b></a> ·
  <a href="https://www.linkedin.com/in/atilak-modetad-95b727331/">LinkedIn</a> ·
  <a href="mailto:atilak.work@gmail.com">atilak.work@gmail.com</a>
</p>

## About

- **Published.** First author of an ICCI 2025 paper on entropy-guided knowledge distillation for wound-image classification ([IEEE Xplore](https://ieeexplore.ieee.org/document/10987261)).
- **Now.** Research assistant at KMUTT, designing a multi-view rendering and consensus pipeline that detects damage on heritage sites from laser-scan point clouds (private research code).
- **How I write.** Every project below reports its results as logged, with the limits of the evaluation next to them.

## Featured projects

| Project | What it does | Highlights |
|---|---|---|
| [**Entropy-guided KD**](https://github.com/Taiga0727/entropy-guided-kd-wound-classification) | Code for the ICCI 2025 paper: a ResNet-18 learns from a ResNet-34 whose own uncertainty sets the temperature and loss weight per sample | 95.22% against 90.89% for standard KD on 9 wound classes · 49% smaller student · evaluation caveats documented |
| [**FahMai RAG**](https://github.com/Taiga0727/fahmai-rag-intent-aware) | Thai product Q&A over a Markdown knowledge base, 100 multiple-choice questions (Super AI Engineer S6) | Rule-based intent routing · BGE-M3 + BM25 fused with RRF · forced retrieval of named products |
| [**Thai data storytelling**](https://github.com/Taiga0727/thai-data-storytelling-hackathon) | Three open-data notebooks that end in a recommendation: fire risk, university enrollment, rain and floods | Severity scoring · 2024 vs 2025 enrollment shifts · dashboard-ready CSVs |
| [**ML learning notes**](https://github.com/Taiga0727/ml-learning-notes) | SVM on spider vs scorpion photos; DGCNN on ModelNet40 point clouds | Baselines with their mistakes written down |

## Tools

| | |
|---|---|
| **Deep learning & vision** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![fastai](https://img.shields.io/badge/fastai-2BA6CB?style=flat-square) ![Open3D](https://img.shields.io/badge/Open3D-1F6FEB?style=flat-square) ![Albumentations](https://img.shields.io/badge/Albumentations-3F4F75?style=flat-square) |
| **Retrieval & NLP** | ![sentence-transformers](https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![BM25](https://img.shields.io/badge/BM25-5B8DEF?style=flat-square) ![PyThaiNLP](https://img.shields.io/badge/PyThaiNLP-7A5AF8?style=flat-square) |
| **Data & ML** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) |
| **Workflow** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white) |

## Repository standard

Each repository has an MIT licence, a requirements file, Open-in-Colab links, a pipeline diagram and notes on the limits of its results. The paper's model weights ship with SHA-256 checksums.
