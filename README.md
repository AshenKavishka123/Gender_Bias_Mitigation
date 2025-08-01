# Gender Bias Mitigation in GPT-2 Models

This repository contains the implementation and demonstration of a research project focused on **detecting and mitigating gender bias** in GPT-2 language models. The project was conducted as part of an academic module titled:

📘 **Module 3: Detecting and Mitigating Gender Bias in GPT Models**

---

## 📌 Overview

Language models like GPT-2 have demonstrated powerful capabilities in text generation, but they often replicate and reinforce societal biases present in the data they are trained on. This project investigates the presence of **gender bias** in GPT-2 and implements methods to **reduce such bias** through counterfactual data augmentation and fine-tuning.

---

## 🛠️ Technologies Used

- Python 🐍
- Google Colab 📓
- HuggingFace Transformers 🤗
- PyTorch 🔥
- Pandas, Matplotlib, Seaborn 📊
- Git & GitHub 🧑‍💻

---

## 🧪 Module Implementation Steps

1. **Prompt Construction**  
   Developed a set of carefully crafted prompts reflecting different genders in varied contexts (e.g., occupations, personality traits, achievements).

2. **Synthetic Dataset Generation**  
   Generated counterfactual prompt pairs by interchanging gender terms (e.g., "He is a CEO" ↔ "She is a CEO").

3. **Bias Detection & Evaluation**  
   Evaluated GPT-2's responses using lexical analysis and comparative generation.

4. **Counterfactual Data Augmentation**  
   Augmented the dataset to ensure balanced exposure of both gender perspectives.

5. **Fine-tuning GPT-2**  
   Fine-tuned the original GPT-2 model on the augmented dataset to mitigate gender bias.

6. **Post-Mitigation Evaluation**  
   Compared outputs from original and fine-tuned models to validate reduction in bias.

---

## 📈 Evaluation Metrics

The following were used to analyze bias and its reduction:

- **Sentiment Distribution Comparison**
- **Token-Level Lexical Differences**
- **Prompt-Based Output Divergence**
- **Visualizations (Bar Charts, Histograms, Word Clouds)**

---

## 📂 Repository Structure

```bash
📁 Gender_Bias_Mitigation/
├── gender_bias_dataset.csv         # Dataset of gendered prompts
├── debiased_gpt2_model_final/     # Fine-tuned GPT-2 model folder
├── Gender_Bias_Mitigation.ipynb   # Colab notebook with full implementation
├── evaluation_charts/             # Optional: charts and graphs for analysis
└── README.md                      # This file
