# Data-ANIP-Challenge
**Auteur : David Akpovi**

## Contexte du projet
L’Agence Nationale d’Identification des Personnes (ANIP) joue un rôle central dans la gestion des données d’état civil au Bénin.  
Ce challenge visait à croiser ces données avec des sources économiques, démographiques et sociales afin d’obtenir une vision intégrée du développement national.

L’objectif global :  
**révéler des tendances cachées, détecter des anomalies, et produire des insights exploitables pour orienter les politiques publiques.**

---

## Structure du projet
Le projet est organisé en **trois tâches principales**, chacune livrée dans un dossier séparé.

### 1. [Tâche 1 – Collecte et Préparation des Données](./Tâche_1)
**Objectif :** construire un dataset fiable, propre et harmonisé à partir de multiples sources ouvertes.  
- Collecte via API (World Bank, etc.)
- Nettoyage et harmonisation des formats, unités et clés (`iso3`, `year`)
- Consolidation multi-sources  
- Contrôle de qualité automatisé  

**Livrables principaux :**
- `dataset_final.csv` (complet)
- `dataset_final_core.csv` (épuré)
- `datasets_exports.zip`
- `Glossaire_des_variables.xlsx`
- `Tache_1_Akpovi_David_Notebook_0610.ipynb`

---

### 2. [Tâche 2 – Exploration et Analyse](./Tache_2)
**Objectif :** analyser les tendances, construire des indicateurs dérivés et préparer les données pour la visualisation.  
- Analyse descriptive et temporelle (1960–2025)
- Détection des anomalies et documentation méthodologique
- Calculs :
  - Croissance annuelle de la population
  - PIB par habitant
  - Indice composite de développement  
- Agrégations par décennie pour intégration Power BI / Dashboard

**Livrables principaux :**
- `dataset_final_enriched.csv`
- `agg_decade_mean.csv`
- `agg_decade_last.csv`
- `eda_anomalies_methodo.txt`
- `Tache_2_Akpovi_David_Notebook_0610.ipynb`

---

### 3. [Tâche 3 – Visualisation et Insights](./Tache_3)
**Objectif :** créer un tableau de bord interactif et raconter une histoire claire à partir des données.  
- Création de KPI (population, PIB, santé, croissance)
- Visualisations temporelles (matplotlib)
- Corrélations économiques/sanitaires
- Dashboard interactif avec **Plotly**
- Export HTML (`evolution_indicateurs.html`) et images statiques

**Livrables principaux :**
- `evolution_indicateurs.html`, `kpi_bar_interactif.html`
- `figs_tache3/`
- `Tache_3_Akpovi_David_Notebook_0610.ipynb`

---

## Données principales
**Sources :**
- Banque mondiale (World Development Indicators)
- WHO, UNDP, et autres portails open data  
- Données harmonisées pour le Bénin (`iso3 = BEN`, 1960–2024)

**Indicateurs clés :**
- Population totale  
- PIB (USD courants)  
- Croissance du PIB réel (%)  
- PIB par habitant (USD)  
- Espérance de vie à la naissance (années)  
- Mortalité maternelle (pour 100 000 naissances vivantes)  
- Indice composite de développement (calculé)

---

## Méthodologie globale
1. **Collecte automatisée** via scripts Python (API + CSV/JSON)
2. **Nettoyage et harmonisation** des formats, unités et années
3. **Analyse exploratoire** et détection des anomalies
4. **Création d’indicateurs dérivés** pour la visualisation
5. **Construction du tableau de bord** interactif (Plotly)


## Organisation des fichiers
## Organisation des fichiers
Data-ANIP-Challenge/
│
├── Tache_1/
│ ├── Tache_1_Akpovi_David_Notebook_0610.ipynb
│ ├── dataset_final.csv
│ ├── dataset_final_core.csv
│ ├── datasets_exports.zip
│ └── Glossaire_des_variables.xlsx
│
├── Tache_2/
│ ├── Tache_2_Akpovi_David_Notebook_0610.ipynb
│ ├── dataset_final_enriched.csv
│ ├── agg_decade_mean.csv
│ ├── agg_decade_last.csv
│ └── eda_anomalies_methodo.txt
│
├── Tache_3/
│ ├── Tache_3_Akpovi_David_Notebook_0610.ipynb
│ ├── evolution_indicateurs.html.html
  ├── kpi_bar_interactif.html
│ └── figs_tache3/
│
└── Rapport_Final-Data_ANIP_Challenge-David_Akpovi.pdf


---

## Résultats et perspectives
- **Amélioration continue des indicateurs :** la croissance démographique s’accompagne d’un allongement de l’espérance de vie.
- **Défis persistants :** mortalité maternelle encore élevée.
- **Lien confirmé entre économie et santé :** corrélation positive entre PIB par habitant et bien-être sanitaire.
- **Prochaines étapes :**
  - Intégrer les données régionales (communes, départements)
  - Automatiser la mise à jour via API
  - Étendre le tableau de bord pour suivi en temps réel

---

## Auteur
**David Akpovi**  
Author & Data Analyst & AI Engineer
[GitHub](https://github.com/davidakpovi) • [LinkedIn](https://linkedin.com/in/davidakpovi)

---
