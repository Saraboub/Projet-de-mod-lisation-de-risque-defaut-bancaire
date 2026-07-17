# Modélisation du risque de défaut de paiement bancaire

Projet réalisé dans le cadre de [nom du cours / M2 Financial Engineering & Fintech, ESC Clermont].

## Contexte
Analyse et modélisation du risque de défaut sur une base simulée de 4 000 clients bancaires.

## Méthodologie
- Analyse exploratoire des données (distributions, valeurs manquantes, valeurs aberrantes)
- Imputation des valeurs manquantes, encodage des variables catégorielles
- Comparaison de deux modèles : régression logistique et Random Forest
- Optimisation des hyperparamètres par validation croisée (GridSearchCV)
- Analyse des erreurs de classification (faux positifs / faux négatifs)

## Résultats clés
- Variables les plus corrélées au risque de défaut : nombre de crédits actifs, score de crédit, salaire mensuel
- Régression logistique : accuracy 88%, ROC-AUC 0.94
- Random Forest : performances quasi parfaites (accuracy 1.00, ROC-AUC 1.00) — à interpréter avec prudence sur un dataset simulé

## Contenu du repo
- `notebook.ipynb` : code complet (Python, pandas, scikit-learn)
- `rapport.pdf` : rapport détaillé
- `presentation.pptx` : support de présentation
- `dataset_bancaire.csv` : jeu de données (simulé)

## Outils
Python, pandas, scikit-learn, matplotlib, seaborn
