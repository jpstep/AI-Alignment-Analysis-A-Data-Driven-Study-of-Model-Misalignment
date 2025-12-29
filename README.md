# AI Alignment Response Analysis

This project explores how large language models respond to alignment-sensitive prompts, with a focus on refusal behaviour, hedging, and safety-related language patterns.

The aim is not to claim definitive alignment evaluation, but to demonstrate a **transparent, data-driven approach** to analysing model behaviour using reproducible methods.

---

## Project Motivation

As AI systems are increasingly deployed in high-stakes contexts, understanding how models respond to sensitive or potentially harmful prompts is critical.

This project was created to:
- Explore practical proxies for alignment-related behaviour
- Demonstrate careful handling of model-generated data
- Apply data analysis techniques to an AI governance problem

---

## Repository Structure

data/
raw/
prompts.csv # Alignment-related prompts
processed/ # Generated responses (excluded from version control)
notebooks/
01_generate_responses.ipynb
02_alignment_analysis.ipynb

---

## Methodology

1. **Prompt Collection**
   - Prompts are curated to probe safety, refusal, and uncertainty behaviours.
   - Stored in `data/raw/prompts.csv`.

2. **Response Generation**
   - Model responses are generated locally using an external API or open-source model.
   - Raw responses are intentionally excluded from version control.

3. **Analysis**
   - Simple, interpretable heuristics are used to flag:
     - Refusal behaviour
     - Hedging / uncertainty language
   - Metrics are aggregated to support comparative analysis.

---

## Limitations

- Alignment is not directly measurable; all metrics are heuristic.
- Regex-based classifiers are coarse and may produce false positives.
- Human annotation would be required for stronger claims.

---

## Future Work

- Human-labelled alignment datasets
- Comparison across multiple models
- More sophisticated NLP classifiers
- Visualisation of behavioural differences

---

## Disclaimer

This project is for research and demonstration purposes only and does not make claims about the safety or alignment of any specific model.
