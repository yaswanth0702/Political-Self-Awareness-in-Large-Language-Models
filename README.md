# Political-Self-Awareness-in-Large-Language-Models


# Political Self-Awareness in Large Language Models

## Overview

This project evaluates the political self-awareness of Large Language Models (LLMs) by analyzing their responses to political fact-check claims. The goal is to understand how different LLMs interpret political statements and whether their responses show awareness, neutrality, or bias.

The project compares multiple open-source and proprietary LLMs using the same dataset and analyzes their responses quantitatively.

The models evaluated in this project include:

- Gemini 2.5 Pro
- Mistral 7B
- LLaMA 3.1 8B

---

## Dataset

Dataset used:

politifact_factcheck_data.json

This dataset contains political claims collected from PolitiFact, including:

- Political statements
- Fact-check information
- Truth labels

This dataset is used to test how each LLM responds to political content.

---

## Project Structure

```
Political-Self-Awareness-in-Large-Language-Models

LLM_Gemini_2.5-pro.ipynb
LLM_Gemini_2.5-pro_results.csv

LLM_Mistral_7b.ipynb
LLM_Mistral_7b_results.csv

LLM_llama_3.1 8b.ipynb
LLM_llama_3.1 8b_results.csv

Results_Comparisition.ipynb

politifact_factcheck_data.json

README.md
```

---

## Methodology

The project follows these steps:

### 1. Load Dataset

The PolitiFact dataset is loaded and preprocessed.

### 2. Generate LLM Responses

Each model:

- Gemini 2.5 Pro
- Mistral 7B
- LLaMA 3.1 8B

is prompted with the same political claims.

The responses are collected and saved.

---

### 3. Store Results

Each model's responses are saved in separate CSV files:

- Gemini results
- Mistral results
- LLaMA results

---

### 4. Compare Model Performance

The results comparison notebook evaluates:

- Response patterns
- Agreement with fact-check labels
- Consistency across models

---

## Results

The comparison shows differences in how each model interprets political statements.

Key observations:

- Some models provide neutral responses.
- Some models show stronger alignment with fact-check labels.
- Response consistency varies across models.

The results CSV files contain the detailed outputs for each model.

---

## Technologies Used

- Python
- Jupyter Notebook
- Large Language Models
- Pandas
- NumPy

Models Used:

- Gemini 2.5 Pro
- Mistral 7B
- LLaMA 3.1 8B

---

## How to Run

Step 1: Clone the repository

git clone https://github.com/yourusername/Political-Self-Awareness-in-Large-Language-Models.git

Step 2: Install dependencies

pip install pandas numpy

Step 3: Open Jupyter Notebook

jupyter notebook

Step 4: Run notebooks

Run:

- LLM_Gemini_2.5-pro.ipynb
- LLM_Mistral_7b.ipynb
- LLM_llama_3.1 8b.ipynb
- Results_Comparisition.ipynb

---

## Conclusion

This project demonstrates how different Large Language Models respond to political claims and evaluates their political self-awareness.

The results show that LLM responses vary depending on the model architecture and training.

This analysis helps understand model behavior in politically sensitive contexts.

---

## Author

Yaswanth Podapati

MS Computer Science
