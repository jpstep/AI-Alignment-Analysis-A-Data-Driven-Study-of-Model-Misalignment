# AI Alignment Analysis: A Data-Driven Study of Model Misalignment

## 🔍 Overview
This project explores **AI alignment failures** from a data analysis perspective.  
Using a **synthetically generated dataset of language-model responses**, it aims to identify patterns of misalignment across ethically ambiguous, dual-use, and safety-critical prompts.

The goal is not to optimise or deploy models, but to **quantitatively analyse where and how alignment failures occur**, using reproducible data analysis methods.

---

## 📊 Dataset Creation
- Prompts are manually designed across **alignment-relevant categories**
- A single language model is used to generate responses under consistent conditions
- Only **prompt templates** are version-controlled
- Model responses are generated locally and excluded from version control

Each response is later annotated for:
- Alignment violation (binary)
- Violation type
- Severity level (1–3)

This mirrors real-world **AI safety evaluation workflows**.

---

## 🧪 Methodology
1. Prompt design and categorisation  
2. Response generation (reproducible, controlled conditions)  
3. Data cleaning and feature engineering  
4. Exploratory data analysis (EDA)  
5. Creation of custom alignment and risk metrics  
6. Visualisation of misalignment patterns  

---

## 📈 Example Research Questions
- Which prompt categories produce the highest misalignment rates?
- Are longer or more detailed responses more likely to violate alignment?
- Do certain violation types cluster around specific prompt categories?
- How does violation severity vary across prompt types?

---

## ⚠️ Ethical Considerations
- All data is **synthetic** and non-deployable
- Annotations involve subjective judgement
- Results should not be used to rank or benchmark real-world models
- The project focuses on **analysis**, not enforcement or optimisation

---

## 🔮 Future Work
- Compare responses across multiple models
- Add inter-annotator agreement analysis
- Perform time-based or prompt-drift analysis
- Produce policy-oriented risk summaries

---

## 🛠 Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebooks  

---

## 📄 License
This project is licensed under the MIT License.
