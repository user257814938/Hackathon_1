Lien Slides : https://github.com/user257814938/Hackathon_1/blob/main/Slides.pptx

Lien Loom : https://www.loom.com/share/43cc245dc6a9446b8415e841726ec995?t=178

---

## 🎯 Nom du projet  
**Subject 3: Exploring Employee Attrition and Performance in a Corporate Environment**

---

## 🧠 Qu’est-ce que c’est ?  

Ce projet a été réalisé dans le cadre d’un **Hackathon Data Science**.  
Il vise à explorer les **facteurs qui influencent l’attrition (turnover)** et la **performance des employés** au sein d’une entreprise à l’aide du jeu de données IBM HR Analytics.  

L’objectif principal est d’identifier les variables les plus corrélées au départ des employés (âge, salaire, satisfaction, équilibre vie pro/perso, etc.) afin de proposer des **recommandations concrètes** pour améliorer la rétention et la satisfaction des collaborateurs.

---

## 💡 Problématique  

- Quels sont les principaux facteurs qui influencent le départ des employés ?  
- Comment l’âge, la rémunération, la satisfaction et les heures supplémentaires impactent-ils la fidélité ?  
- Quelles actions concrètes une entreprise peut-elle mettre en place pour réduire le turnover ?  

---

## ⚙️ Outils et technologies utilisés  

- **Langage :** Python 3  
- **Environnement :** Google Colab  
- **Bibliothèques principales :**  
  - `pandas` → manipulation et nettoyage des données  
  - `numpy` → calculs et transformations numériques  
  - `matplotlib` et `seaborn` → visualisations et graphiques  
  - `scipy` → statistiques et corrélations  
- **Source des données :**  
  [IBM HR Analytics Employee Attrition & Performance Dataset](https://www.ibm.com/analytics/data)  
- **Version finale du projet :** `projet/version_2.ipynb`  

---

## 📊 Fonctionnalités principales  

- **Import et nettoyage des données**  
  Gestion des valeurs manquantes, suppression des doublons, encodage des variables catégorielles.  

- **Feature Engineering**  
  Création de nouvelles variables : `Attrition_Flag`, `AgeGroup`, `IncomeNorm`, `OverTime_Flag`.  

- **Analyse exploratoire (EDA)**  
  Étude de la distribution des variables clés : âge, salaire, satisfaction, distance, poste, etc.  

- **Visualisations**  
  Graphiques comparant l’attrition selon :  
  - Département  
  - Équilibre vie pro/perso  
  - Satisfaction au travail  
  - Salaire mensuel  
  - Distance domicile-travail  

- **Corrélations**  
  Analyse des relations entre `Attrition_Flag` et les autres variables (âge, revenu, ancienneté, heures supplémentaires).  

- **Insights & Storytelling**  
  Interprétation des résultats pour comprendre les causes du turnover.  

- **Conclusion & Recommandations**  
  Proposition d’actions RH concrètes pour réduire l’attrition et améliorer la performance.  

---

## 🧩 Résultats obtenus  

- Le **taux d’attrition global** est d’environ **17 %**.  
- Les **jeunes employés** (moins de 35 ans) et les **salaires faibles** sont les plus touchés.  
- Les employés faisant **beaucoup d’heures supplémentaires** présentent un taux de départ plus élevé.  
- Une **satisfaction faible** et un **déséquilibre vie pro/perso** augmentent significativement le turnover.  
- Les **revenus, l’âge et l’ancienneté** ont une corrélation négative avec l’attrition.  

---

## 🚀 Comment exécuter le projet  

1. **Cloner le dépôt GitHub :**  
   ```bash
   git clone https://github.com/user257814938/Hackathon_1.git
   ```
2. **Ouvrir le notebook dans Google Colab ou Jupyter :**  
   ```bash
   cd Hackathon_1/projet
   ```
   Puis ouvrir le fichier :  
   `version_2.ipynb`

3. **Installer les dépendances (si besoin) :**  
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```

4. **Exécuter les cellules dans l’ordre** pour :  
   - Charger le dataset  
   - Nettoyer les données  
   - Effectuer l’analyse et les visualisations  
   - Lire les conclusions  

---

## 🧭 Recommandations générales  

- **Revaloriser les salaires** des postes à forte pression (Sales, R&D).  
- **Réduire les heures supplémentaires** ou mieux les compenser.  
- **Améliorer la satisfaction au travail** par la reconnaissance et la formation.  
- **Favoriser la flexibilité** (télétravail, équilibre vie pro/perso).  
- **Mettre en place un suivi régulier** via un tableau de bord RH pour mesurer l’impact des actions.

---

## 📁 Structure du projet  

```
Hackathon_1/
│
├── Dataset/
│   ├── raw/                          # Données brutes
│   └── processed/                    # Données nettoyées
│
├── projet/
│   ├── version_1.ipynb               # Première version du projet
│   └── version_2.ipynb               # Version finale du notebook
│
├── README.md                         # Documentation du projet
└── requirements.txt                  # Librairies nécessaires (optionnel)
```

---

## 🏁 Conclusion  

Ce projet démontre l’importance des données RH dans la compréhension du turnover et de la performance des employés.  
Grâce à l’analyse des variables clés et à la visualisation des corrélations, il propose des pistes concrètes pour **optimiser la politique RH et renforcer la rétention du personnel**.




