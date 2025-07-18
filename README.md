Voici ton fichier `README.md` **corrigé, structuré et prêt à être utilisé** avec un format professionnel et adapté à GitHub ou tout dépôt de code :

---

````markdown
# 🏡 SalesHouses – Estimation intelligente de prix immobiliers au Maroc

## 🎯 Objectif du projet

Ce projet a été développé dans le cadre d’un challenge d’intelligence artificielle avec **Simplon Academy**, pour la société fictive **SalesHouses**, une plateforme marocaine d’annonces immobilières.

L’objectif est de créer un **modèle de prédiction du prix des appartements** au Maroc à partir de leurs caractéristiques (ville, surface, nombre de chambres, équipements, etc.), et de le déployer dans une **application web interactive** avec Streamlit.

---

📅 **Durée du projet** : du 14 au 18 juillet 2025

---

## 🧪 Méthodologie

1. **Chargement des données**
2. **Analyse exploratoire (EDA)** : visualisations, statistiques, corrélations
3. **Nettoyage des données** :
   - Gestion des valeurs manquantes
   - Traitement des valeurs aberrantes (outliers)
   - Encodage des variables catégorielles
4. **Mise à l’échelle des variables**
5. **Modélisation supervisée** avec plusieurs algorithmes :
   - Régression linéaire
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - SVR (Support Vector Regressor)
6. **Évaluation par validation croisée**
7. **Optimisation des hyperparamètres** (GridSearchCV)
8. **Sauvegarde du meilleur modèle**
9. **Déploiement via une application Streamlit**

---

## 🗂️ Structure des fichiers

| Fichier / Dossier        | Description |
|--------------------------|-------------|
| `appartements.csv`        | Données d’entraînement contenant les caractéristiques des biens immobiliers |
| `model_training.ipynb`    | Code source pour la préparation des données, l'entraînement des modèles et leur évaluation |
| `model.pkl`               | Modèle ML final sauvegardé (Gradient Boosting Regressor) |
| `streamlit_app.py`        | Application web Streamlit pour l’estimation de prix |
| `requirements.txt`        | Liste des dépendances Python nécessaires |
| `README.md`               | Documentation du projet (ce fichier) |

---

## 🚀 Instructions pour exécuter le projet

### 1. Cloner le dépôt

```bash
git clone <url-du-dépôt>
cd saleshouses-estimateur
````

### 2. Installer les dépendances

```bash
pip install -r requirements.txt
```

### 3. Lancer l’application Streamlit

```bash
streamlit run streamlit_app.py
```

---

## ✅ Résultats

* **Modèle retenu** : *Gradient Boosting Regressor*
* **Score R² obtenu** : **0.94** (sur des données bruitées)
* **Justification** : Ce modèle a surpassé les autres en termes de performance et de stabilité. Il gère bien les non-linéarités et les valeurs extrêmes, offrant des prédictions plus fiables dans un contexte réel.

### 🔍 Comparaison des performances :

| Modèle                         | Score R²                       |
| ------------------------------ | ------------------------------ |
| Régression Linéaire            | 0.52                           |
| Random Forest Regressor        | 0.91                           |
| SVR (Support Vector Regressor) | **-1.17** (mauvais ajustement) |

> 📝 **Remarque** : Le SVR a donné un score R² négatif, ce qui indique une mauvaise capacité à généraliser sur les données test. Il n’est donc pas adapté dans ce contexte.

---

## 👩‍💻 Autrice

* **Nom** : REHMI SALMA
* **Contact** : [salmarehmi11@gmail.com](mailto:salmarehmi11@gmail.com)

---
