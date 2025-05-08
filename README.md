# 🚀 Project Overview
Fraudulent healthcare claims cost the system billions annually. While traditional fraud detection models rely heavily on structured data (e.g., claim amount, diagnosis codes), a large portion of valuable insights often remains hidden in unstructured fields like treatment descriptions and physician notes.

This project addresses that gap by building an ensemble system that combines:

Classical ML models trained on structured data.

A fine-tuned BERT model for unstructured clinical text.

A meta-classifier that stacks both outputs for final fraud prediction.

## 🔍 Key Features
📊 Exploratory Data Analysis (EDA): Understanding trends in claim frequency, provider behavior, diagnosis distributions, and class imbalances.

🛠️ Feature Engineering: Derived risk features from provider history, claim amounts, and ICD/CPT code patterns.

🤖 ML Models: Trained and evaluated Logistic Regression, Random Forest, and Decision Trees for baseline performance.

💬 NLP with BERT: Fine-tuned BERT on physician/treatment notes to predict the fraud probability from unstructured text.

🔗 Model Stacking: Combined structured model predictions with BERT outputs into a meta-classifier for enhanced performance.

✅ Evaluation Metrics: Focused on Recall and AUC-ROC due to the criticality of catching fraud early.

## 📈 Results
Final Model: Meta-classifier combining structured + unstructured models

Recall: ~92%

AUC-ROC: 0.95

# ⚠️ Prioritized high-risk claim detection to improve audit efficiency and resource allocation.

