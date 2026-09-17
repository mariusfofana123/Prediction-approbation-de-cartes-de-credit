# 💳 Predicting Credit Card Approvals

## 🎯 Objectif du Projet
L'objectif de ce projet est de concevoir un modèle de Machine Learning capable d'automatiser l'approbation des demandes de cartes de crédit. En s'appuyant sur des métriques financières et personnelles, le modèle prédit si une demande doit être acceptée ou refusée, optimisant ainsi le processus d'évaluation bancaire.

## 🛠️ Technologies & Bibliothèques
* **Python 3.x**
* **Pandas & NumPy** : Nettoyage et prétraitement des données
* **Scikit-Learn** : Normalisation (`StandardScaler`), séparation des jeux de données (`train_test_split`) et modélisation (`LogisticRegression`, `GridSearchCV`)

## 📊 Données Utilisées
Le jeu de données provient du *UCI Machine Learning Repository* (`cc_approvals.data`). Il contient des variables anonymisées représentant diverses caractéristiques financières, démographiques et l'historique de crédit des demandeurs.

## 🔬 Méthodologie
1. **Exploration & Nettoyage :** Traitement des valeurs manquantes et encodage des variables catégorielles.
2. **Préparation des données :** Séparation en ensembles d'entraînement/test et normalisation des variables numériques.
3. **Modélisation :** Entraînement d'un modèle de régression logistique.
4. **Optimisation :** Réglage des hyperparamètres via recherche sur grille (`GridSearchCV`) pour maximiser la précision.

## 🚀 Comment exécuter le projet

**1. Cloner le dépôt :**
```bash
git clone https://github.com/mariusfofana123/Prediction-approbation-de-cartes-de-credit.git
cd Prediction-approbation-de-cartes-de-credit


2. Créer et activer un environnement virtuel :
'''bash
python3 -m venv venv
source venv/bin/activate

3. Installer les dépendances :
'''bash
pip install -r requirements.txt


4. Lancer le notebook :
'''bash
jupyter notebook Notebooks/analyse.ipynb