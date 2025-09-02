# kaggle-game-adoption-prediction-2025
Compétition Kaggle (Data Mining 2025) – pipeline ML multi-classes (LightGBM OvO, Optuna) pour prédire le premier jeu installé le mois suivant.

# Prédiction d’adoption de jeux – Kaggle (Data Mining 2025)

Projet académique réalisé lors du cours **Techniques d’exploitation de données (HEC Montréal)**.  
Objectif : prédire quel jeu un joueur installera en premier le mois suivant (`aucun`, `jeu A`, `jeu B`, `jeu C`).  
Résultat : **4ᵉ place sur 17 équipes** 

**Approche :**
- Modèle **LightGBM One-vs-One** avec optimisation **Optuna**
- Rééquilibrage des classes, features croisées/polynomiales, stacking
- Validation croisée stratifiée pour robustesse

**Repo :**
- Notebooks (exploration & modèle final)
- Données d’exemple simulées
- Résultats et métriques finales
