# Multimodal NLP Interview Evaluation

This project predicts **interview performance and excitement scores** using **natural language processing (NLP)** and **prosodic speech features**, based on the MIT Interview dataset. We developed explainable models using TF-IDF, Word2Vec, and audio-based features, combining them in a multimodal pipeline.

---

## Key Features

-  **Language Modeling** with TF-IDF & Word2Vec
-  **Prosodic Features** (e.g., pitch, intensity) extracted from audio
-  **Multimodal Machine Learning** using Random Forest and Feedforward Neural Networks
-  **Model Explainability** using SHAP and Feature Correlation
-    Evaluated with Pearson correlation and Relative Error (5-fold CV)

---

## Structure

```bash
├── TransformerModel.ipynb       # Transformer-based language exploration
├── Report.pdf                   # Final write-up and results
├── data/                        # (optional) Dataset folder (excluded if too large)
├── figures/                     # Plots and visualizations
├── models/                      # Saved models (optional)
└── README.md                    # This file
