# Financial News Sentiment Analysis 📰

## Contexte
Classification automatique du sentiment de news financières
4 846 news · 3 classes · Positive / Negative / Neutral

---

## Stack technique
Python · BERT · TF-IDF · scikit-learn · PyTorch · LIME · Pandas · Kaggle GPU

---

## Résultats

| Modèle | Accuracy | Recall Negative |
|---|---|---|
| TF-IDF + Logistic Regression | 72% | 67% |
| BERT ✓ | **85%** | **88%** |

---

## Structure du projet

- Phase 1 : EDA & Nettoyage texte
- Phase 2 : Vectorisation TF-IDF — baseline
- Phase 3 : Modélisation BERT — modèle avancé
- Phase 4 : Interprétabilité LIME

---

## Top mots influents (LIME)
Explication locale des prédictions — mots clés par sentiment

---

## Comment reproduire

1. Accepter les règles sur kaggle.com
2. Activer GPU T4 x2
3. Ouvrir le notebook Kaggle
4. Run All

---

## Dataset
[Sentiment Analysis for Financial News — Kaggle](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news)
