# Prédiction de la Dépression Modérée à Sévère (PHQ-9 ≥ 10)

Ce projet utilise des données nutritionnelles, démographiques et cliniques pour prédire le risque de dépression modérée à sévère grâce à un modèle de régression logistique Lasso optimisé.

---

## À propos

- Nettoyage et préparation des données (gestion des NaN, encodage catégoriel, standardisation)
- Modélisation : Lasso avec descente de gradient pondérée
- Analyse statistique : t-tests sur variables nutritionnelles, test du Chi2 sur variables catégorielles
- Évaluation : classification report, accuracy, validation des imputations

---

## Fichiers

- `depression_prediction.ipynb` : Notebook complet avec code, résultats, et explications

---

## Installation

```bash
pip install numpy pandas scikit-learn scipy matplotlib seaborn
