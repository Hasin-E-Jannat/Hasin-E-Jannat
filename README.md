<h1 align="center">Hi, I'm Hasin 👋</h1>

<p align="center">
  <b>Researcher · AI/NLP Engineer · Government ICT, Bangladesh</b><br/>
  Feature Selection &nbsp;|&nbsp; Hyperspectral Imaging &nbsp;|&nbsp; Intrusion Detection &nbsp;|&nbsp; Low-Resource Bengali NLP &nbsp;|&nbsp; RAG
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?user=SZoIfV0AAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/hasin-e-jannat-634279128/| E"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:hasin.cse@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
</p>

---

## 👨‍💻 About Me

I am an Assistant Programmer at the **ICT Division, Government of Bangladesh**, where I build AI/NLP systems that automate government document workflows in Bengali. I am also pursuing an **MSc in Computer Science and Engineering at the Military Institute of Science and Technology (MIST), Dhaka**.

My work sits at the intersection of two questions:

- **How can we extract more signal from high-dimensional remote sensing data with compact, well-designed deep models?**
- **How can we make modern NLP and LLM systems work reliably for a low-resource language like Bengali, in real public-sector settings?**

I am seeking a **fully funded PhD** in AI/ML and open to research collaborations, especially in hyperspectral imaging, Bengali NLP, and applied AI for governance.

---

## 🔬 Research

### 1. Mutual-Information-Driven Feature Selection
A line of work asking one question: *when PCA alone is not enough, can mutual information with the class labels pick better features?* I have studied it across three settings.

| Year | Setting | Approach | Result |
|---|---|---|---|
| 2017 | Hyperspectral imaging (AVIRIS Indian Pines) | PCA + normalized mutual information + RBF-kernel SVM | 99.3% accuracy on a four-class subset, vs 98.99% for PCA alone |
| 2022 | Network intrusion detection (KDD Cup '99, 10%) | Robust PCA (low-rank + sparse decomposition) + mutual information + SVM | ~99.8% accuracy with 4 features, vs 89.68% for PCA |
| MSc thesis | Hyperspectral deep learning (Indian Pines) | PCA-MI-ResDenseNet | *Accepted in IDAA 2025 conference and under review for Taylor&Francis* |

🗂️ Code: [`PCA-MI-ResDenseNet`](https://github.com/YOUR_USERNAME/PCA-MI-ResDenseNet)

### 📄 Publications

1. **M. A. Hossain, Hasin-E-Jannat, B. Ahmed, and M. A. Mamun**, "Feature Mining for Effective Subspace Detection and Classification of Hyperspectral Images," *2017 International Conference on Electrical, Computer and Communication Engineering (ECCE)*, Cox's Bazar, Bangladesh, pp. 544-547, 2017. [[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/7912965)]
2. **Hasin E Jannat, M. M. Rahman, S. K. Dey, and A F M M. Islam**, "Mutual Information on Low-rank Matrix for Effective Intrusion Detection," *2022 4th International Conference on Sustainable Technologies for Industry 4.0 (STI)*, Dhaka, 2022. [[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10103298)]
3. *PCA-MI-ResDenseNet for hyperspectral image classification*, Accepted in IDAA 2025 conference and under review for Taylor&Francis, Journal **in preparation**.

### 2. Low-Resource Bengali NLP & Government AI
**Lipi AI / BanglaGovBot:** an end-to-end Bengali government document automation system.

- **Dataset:** BanglaGovDoc-4275, a curated corpus of Bengali government documents
- **Classification:** fine-tuned BanglaBERT, **81% accuracy, 0.8055 macro-F1**
- **Retrieval:** FAISS-based RAG pipeline for grounded document generation
- **Generation:** locally hosted LLM (Ollama, Llama 3.2 3B), so sensitive documents stay on-premise
- **Stack:** FastAPI backend, React frontend
- 🗂️ Code: [`Lipi-AI`](https://github.com/YOUR_USERNAME/Lipi-AI)

---

## 🧰 Technical Arsenal

### 🧠 Machine Learning & Deep Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

- **Computer Vision / Remote Sensing:** hyperspectral classification, PCA + mutual information feature selection, ResNet/DenseNet hybrids
- **Feature Selection & Dimensionality Reduction:** PCA, Robust PCA (low-rank + sparse decomposition), mutual information / NMI, SVM with RBF kernel and cross-validation
- **Cybersecurity ML:** network intrusion detection on KDD Cup '99
- **NLP:** BanglaBERT fine-tuning, text classification, dataset construction
- **LLM Systems:** RAG pipelines, FAISS vector search, local LLM deployment, prompt engineering, few-shot prompting

### ⚙️ Backend & Frontend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

### 🛠️ Tools & Workflow
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)
Web scraping for corpus building · Model evaluation (OA / AA / Kappa, Accuracy, Macro-F1) · Reproducible experiments · scientific writing

---

## 📌 Featured Projects

| Project | Description | Stack |
|---|---|---|
| [**PCA-MI-ResDenseNet**](https://github.com/YOUR_USERNAME/PCA-MI-ResDenseNet) | Hyperspectral image classification framework benchmarked on Indian Pines | Python, PyTorch |
| [**Lipi AI / BanglaGovBot**](https://github.com/YOUR_USERNAME/Lipi-AI) | Bengali government document classification, retrieval, and generation | FastAPI, React, FAISS, Ollama |
| [**BanglaGovDoc-4275**](https://github.com/YOUR_USERNAME/BanglaGovDoc-4275) | Bengali government document dataset for classification | Python, HF Datasets |

---

## 🎯 Currently

- 📝 Preparing the journal submission on PCA-MI-ResDenseNet
- 🔧 Strengthening the evaluation and academic framing of Lipi AI
- 🌏 Preparing applications for fully funded graduate programs and research collaborations
- 📚 Exploring low-resource NLP, efficient RAG, and compact models for remote sensing

---

## 🤝 Let's Collaborate

I would be glad to hear from you if you work on:

- Hyperspectral / remote sensing deep learning
- Feature selection and robust dimensionality reduction (including for intrusion detection)
- Bengali and other low-resource language NLP
- Trustworthy, on-premise AI for public-sector use

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&hide_border=true" height="150"/>
</p>

<p align="center"><i>"Making AI work for Bangladesh, one dataset at a time."</i></p>
