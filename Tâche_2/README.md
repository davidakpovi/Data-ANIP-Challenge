# Tâche 2 – Exploration et Analyse

## Objectif
Explorer le dataset consolidé afin d’identifier des tendances, corrélations et anomalies, et produire des indicateurs dérivés exploitables dans Power BI.

## Étapes principales
1. Analyse descriptive : tendances temporelles et statistiques de base.
2. Création d’indicateurs dérivés :
   - Croissance annuelle de la population (%)
   - PIB par habitant (USD)
   - Indice composite de développement (PIB + santé + mortalité)
3. Détection d’anomalies :
   - Valeurs aberrantes ou négatives
   - Doublons sur (`iso3`, `year`)
4. Agrégations temporelles :
   - Moyennes et dernières valeurs par décennie.
5. Exports :
   - `dataset_final_enriched.csv`
   - `agg_decade_mean.csv`, `agg_decade_last.csv`
   - Journal : `eda_anomalies_methodo.txt`

## Livrables
- `dataset_final_enriched.csv` (dataset enrichi)
- `agg_decade_mean.csv` / `agg_decade_last.csv`
- `eda_anomalies_methodo.txt` (anomalies et choix méthodologiques)
- `Notebook_Tache_2.ipynb`

## Points clés
- Mise en place d’indicateurs économiques et sociaux combinés.
- Documentation des anomalies pour assurer la traçabilité.
- Données prêtes pour l’intégration dans un tableau de bord interactif.
