<!-- 
  =============================================================
  ⚡ DYNAMIC UPDATE WORKFLOW SETUP:
  To make the "Recent GitHub Activity" section below update automatically:
  1. In your GitHub repository (Dakshified/Dakshified), create a folder structure:
     .github/workflows/
  2. Inside that folder, create a file named:
     update-readme.yml
  3. Paste the following YAML code into that file:

name: Update README Activity

on:
  schedule:
    - cron: '*/30 * * * *' # Runs every 30 minutes
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  =============================================================
-->


# 👋 Hello My name is Daksh Bhardwaj!

**Machine Learning Engineer & Full-Stack Developer** based in Pune, India.  
*Translating complex datasets into intelligent algorithms and scalable user experiences.*

**[LinkedIn](https://www.linkedin.com/in/daksh-bhardwaj-40b533331/) | [Email](mailto:bhardwajdaksh1409@gmail.com) | [GitHub](https://github.com/Dakshified)**

---

### 💡 My Philosophy & "Why I Code"

I build machine learning models and full-stack software to transform massive datasets into clean, actionable, and intelligent tools. I believe that software engineering is a continuous loop of learning, optimization, and automation—writing code that doesn't just run, but makes systems faster, smarter, and more reliable.

---

### 🎓 Education & Learning Log

- **B.Tech in Computer Science (Artificial Intelligence)** | Vishwakarma Institute of Technology, Pune (2024 - 2028 | CGPA: **9.06**)
- 📖 **My Learning Log**: I document academic notes, deep dives into ML algorithms (such as Cross-Validation and Dimensionality Reduction), and LaTeX mathematical breakdowns in my public learning repositories.

---

### 📂 Featured Projects (The STAR & "Proof of Thought" Approach)

Here are the signature projects that showcase my engineering methodology:

#### 🔗 Campus Trust — Blockchain Certificate Verification Platform
*Decentralized credential ledger for secure institutional verification.*
- **Situation/Task**: Establish a secure, instant, and tamper-proof verification channel for academic certificates to combat credential fraud.
- **Action**: Architected a decentralized system on the Algorand blockchain using PyTeal smart contracts, implementing institutional role-based access control and optimized Flask backends.
- **Result**: Reduced verification time from days to under 10 seconds across 300+ credentials with zero data tampering.
- **💡 Key Challenge Faced**: Managing gas efficiency and complex transaction state on-chain with PyTeal's assembly-like constraints. Resolved this by optimizing state storage variables and using minimal TEAL opcodes.

#### 🤖 SahAI — Your Placement Assistant
*ML-driven interview assessment pipeline.*
- **Situation/Task**: Automate the labor-intensive process of reviewing open-ended, technical interview responses for college placement drives.
- **Action**: Developed an end-to-end NLP assessment pipeline. Leveraged Sentence Transformers for semantic response evaluation, spaCy for keyphrase detection, and a Random Forest model for overall speech and content scoring.
- **Result**: Achieved an 87% scoring accuracy across 250+ candidate responses, automating workflows that previously required manual review.
- **💡 Key Challenge Faced**: High vocabulary variance of candidate responses caused false-negatives in semantic scoring. Solved this by designing a hybrid scoring model that weights cosine-similarity of sentence embeddings alongside custom keyword presence.

#### 🔍 ElectroLens — Hybrid AI Educational Platform
*Real-time component recognition and adaptive quiz engine.*
- **Situation/Task**: Provide students with an interactive, real-time tool for identifying and learning about electronic components on edge devices.
- **Action**: Trained and compressed a MobileNetV2 computer vision model to identify 14 component categories. Deployed a FastAPI backend interfacing with a Flutter mobile app, integrated with Gemini 1.5 Flash for generating adaptive quizzes.
- **Result**: Attained a 90.4% recognition accuracy with under 200ms latency, validated on-site with 30 student volunteers.
- **💡 Key Challenge Faced**: High latency on low-end mobile devices. Solved this by implementing model quantization on the MobileNetV2 weights and caching Gemini prompt contexts on the backend.

#### 📈 CAP MADE EASY — Perfect College Finder
*Recommendation engine for college admissions.*
- **Situation/Task**: Guide high school graduates through the complex, multi-round Maharashtra CAP college allocations.
- **Action**: Built a recommendation engine using Random Forest and Reinforcement Learning, trained on a historic dataset of 10,000+ CAP round admission records.
- **Result**: Successfully generated optimized college shortlists and choice codes for over 400 students.
- **💡 Key Challenge Faced**: Overcoming data sparsity and class imbalance in student preferences. Solved this by applying synthetic minority over-sampling (SMOTE) to rare choices and using a custom reward function in the reinforcement learning model.

---

### ⚡ Recent GitHub Activity
<!-- The section below updates dynamically using GitHub Actions. Do not edit this manually. -->
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Dakshified&theme=react-dark&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ff8b55&area=true&hide_border=true" alt="GitHub Activity Graph" width="100%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dakshified&theme=dark&hide_border=true&background=0d1117&fire=ff8b55&ring=58a6ff&stroke=58a6ff&currStreakNum=58a6ff&sideNums=c9d1d9&sideLabels=c9d1d9&currStreakLabel=58a6ff" alt="GitHub Streak" width="100%" />
</p>

---

### 🛠️ Tech Stack & Skills

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat-square&logo=cplusplus&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=flat-square&logo=c&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-00758F?style=flat-square&logo=mysql&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E) |
| **ML & Data Science** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat-square&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat-square&logo=TensorFlow&logoColor=white) `Sentence Transformers` `spaCy` `Pandas` `NumPy` `PyTorch` |
| **Web & App** | ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=flat-square&logo=redux&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=flat-square&logo=flask&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=flat-square&logo=flutter&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white) |
| **Databases** | ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat-square&logo=mongodb&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=flat-square&logo=sqlite&logoColor=white) |
| **Tools & DevOps** | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat-square&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white) `LaTeX` |
