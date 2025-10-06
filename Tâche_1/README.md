# Tâche 1 – Collecte et Préparation des Données

## Objectif
Collecter, nettoyer et harmoniser des données issues de sources ouvertes afin de constituer un dataset final unique et prêt à l’analyse.

## Étapes principales
1. Collecte de données depuis les API et portails open data (Banque Mondiale, etc.)
2. Nettoyage : standardisation des noms de colonnes, correction des types, suppression des valeurs aberrantes.
3. Harmonisation : alignement des clés (`iso3`, `year`) et cohérence entre les sources.
4. Consolidation : fusion des datasets en un seul fichier central.
5. Export :
   - `dataset_final.csv` : version riche (avec métadonnées)
   - `dataset_final_core.csv` : version épurée (7 indicateurs principaux)
   - Contrôle de qualité automatique.

## Livrables
- `dataset_final.csv`
- `dataset_final_core.csv`
- `datasets_exports.zip`
- `Tache_1_Akpovi_David_Notebook_0610.ipynb` (code de collecte, nettoyage, harmonisation)
- `Glossaire_des_variables.xlsx`

## Points clés
- Données cohérentes et normalisées pour la période 1960–2025.
- Indicateurs : population, PIB, croissance, espérance de vie, mortalité maternelle.
- Qualité validée via contrôle automatisé des clés et des valeurs manquantes.
