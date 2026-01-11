# 🧠 An Ethical Audit of Occupational Bias in Generative AI Image Models

This project conducts an **ethical audit of occupational bias** in **generative AI image models**, focusing on how professions are visually represented by models such as **Stable Diffusion** and **DALL·E**.  
The study analyzes **gender and racial representation** in AI-generated images to understand how societal stereotypes are reproduced and amplified.

---

## 🎯 Project Objectives
- Audit **gender and racial bias** in AI-generated occupational images
- Compare bias patterns across **multiple generative AI models**
- Build a **reproducible, API-based auditing framework**
- Highlight ethical risks and provide insights for **Responsible AI**

---

## 📊 Dataset & Image Generation
- Images generated using **automated API calls**
- Models used:
  - Stable Diffusion (via Hugging Face)
  - DALL·E (via OpenAI API)
- Dataset includes:
  - **10 neutral occupations**
  - **100+ generated images**
  - Consistent prompt templates to avoid prompt bias

Example prompt:
> “A realistic professional portrait of a [profession] at work, photographed in a neutral environment.”

📄 Based on the accompanying research paper :contentReference[oaicite:0]{index=0}

---

## ⚙️ Methodology
- API-based automated image generation using Python
- Manual and assisted annotation of:
  - Gender presentation
  - Racial appearance
- Metadata stored in structured CSV format
- Combination of **quantitative metrics** and **qualitative visual analysis**

---

## 📐 Bias Evaluation Metrics
- **Gender Representation Ratio (GRR)**
- **Racial Diversity Index (RDI)**
- Cross-occupation comparison
- Cross-model comparison

Balanced representation is expected near **50%**, with large deviations indicating bias.

---

## 🏆 Key Findings
- Strong **male dominance** in technical and leadership roles (e.g., doctor, engineer, CEO)
- Care-oriented professions more frequently depicted as female
- Majority of generated subjects appeared **Western and white**
- Both Stable Diffusion and DALL·E showed similar bias trends, with minor variation

---

## 🛠️ Technologies Used
- Python
- OpenAI API (DALL·E)
- Hugging Face Diffusers (Stable Diffusion)
- Pandas, NumPy
- Computer Vision APIs (for verification)
- Manual human evaluation

---

## ⚖️ Ethical Significance
- Highlights **representational harm** in generative AI
- Demonstrates how AI imagery can reinforce societal stereotypes
- Emphasizes the need for:
  - Dataset transparency
  - Bias auditing
  - Responsible deployment of generative models

---

## 🔮 Future Work
- Larger occupation sets and multilingual prompts
- Fully automated demographic detection
- Bias-mitigation techniques (prompt conditioning, fairness filters)
- Open-source bias auditing tools for generative AI

---
