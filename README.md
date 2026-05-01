# 📊 Analyse Financière des Banques au Cameroun

> **Quelle banque est la plus rentable et dans quelle ville investir ?**  
> Une analyse exploratoire de données (EDA) pour transformer des données financières en décisions stratégiques.

---

## 🗂️ Contexte du projet

Dans un environnement économique où les décisions d’investissement doivent être guidées par des données fiables, ce projet analyse les performances financières de plusieurs banques au Cameroun.

L’étude porte sur **4 banques majeures** (BGFI, Ecobank, Société Générale, UBA) réparties dans **4 villes stratégiques** (Douala, Yaoundé, Bafoussam, Garoua), à partir d’un dataset de **1 000 observations**.

🎯 **Objectif :** Identifier les banques les plus rentables et les villes offrant les meilleures opportunités d’implantation.

---

## 🎯 Problématiques

- Quelle banque présente la meilleure rentabilité (revenus vs dépenses) ?
- Quelles villes concentrent les meilleures performances financières ?
- Existe-t-il une relation entre le capital et le bilan financier ?
- Quels outliers peuvent influencer ou biaiser l’analyse ?

---

## 🔍 Méthodologie

Chargement → Nettoyage → Traitement des outliers → Analyse exploratoire → Corrélations → Encodage
### Étapes clés :

- **Nettoyage des données**
  - Vérification des valeurs manquantes et des doublons

- **Traitement des outliers**
  - Détection via la méthode IQR
  - Remplacement par les bornes pour limiter l’impact

- **Analyse exploratoire (EDA)**
  - Analyse univariée : distributions, répartition par banque et par ville  
  - Analyse bivariée : relations entre variables (corrélations, scatterplots)

- **Encodage**
  - Transformation des variables catégorielles avec LabelEncoder

---

## 💡 Résultats clés

- 🥇 **BGFI** présente la meilleure rentabilité (ratio : 2.76), suivie de **UBA** (2.69)
- 📍 **Douala** et **Bafoussam** concentrent les meilleurs bilans financiers
- 📈 Forte corrélation positive entre **capital** et **bilan financier**
- 💸 **UBA** pratique les taux d'intérêt les plus élevés (5.13%), ce qui peut expliquer ses dépenses plus importantes

---

## 📊 Interprétation

Les résultats montrent que le **capital est un facteur déterminant de la performance financière**.  
Par ailleurs, certaines villes offrent un environnement plus favorable à la rentabilité bancaire.

---

## 📌 Recommandation

👉 **BGFI à Douala** apparaît comme la combinaison la plus stratégique, combinant forte rentabilité et volume financier élevé.

---

## 🛠️ Stack technique

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-lightgrey?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-teal)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.4-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)


---

## 📁 Structure du projet

📦 analyse-rentabilite-banques-cameroun
- ┣ 📓 analyse_financiere.ipynb # Notebook principal
- ┣ 📄 dataset_financier.csv # Données
- ┗ 📖 README.md


---

## ▶️ Exécution du projet

-  bash
- git clone https://github.com/lkmc77/analyse-rentabilite-banques-cameroun.git
- cd analyse-rentabilite-banques-cameroun
- pip install pandas numpy matplotlib seaborn scikit-learn
- jupyter notebook analyse_financiere.ipynb

---

## Perspectives d'amélioration

-  Intégration d’un modèle de prédiction de rentabilité
-  Création d’un dashboard interactif (Streamlit / Power BI)
-  Analyse sur des données réelles à plus grande échelle

---

## 👤 Auteur

Projet réalisé dans le cadre d’un portfolio en Data Science.  
N’hésite pas à soutenir le projet en laissant une étoile
