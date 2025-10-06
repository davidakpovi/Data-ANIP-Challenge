# Challenge — Tâche 1 : Collecte & Préparation des Données (Bénin)

Ce dépôt est **complet** et prêt à l'emploi. Il inclut : structure de dossiers, config des sources (Bénin),
notebook, modules Python (collecte/nettoyage/harmonisation + QC), docs (glossaire + dictionnaire des données).

## Structure
```
challenge_tache1_data_pipeline/
├─ config/
│  └─ sources.yml
├─ data/
│  ├─ raw/        # données brutes
│  ├─ interim/    # étapes intermédiaires
│  └─ processed/  # dataset final prêt à l'analyse
├─ docs/
│  ├─ data_dictionary.csv
│  └─ glossary.md
├─ notebooks/
│  └─ 01_collecte_preparation.ipynb
├─ src/
│  ├─ __init__.py
│  ├─ collect.py
│  ├─ clean.py
│  ├─ harmonize.py
│  └─ qc.py
├─ .logs/
└─ requirements.txt
```

## Utilisation rapide
1. `pip install -r requirements.txt`
2. Ouvrir `notebooks/01_collecte_preparation.ipynb`
3. Exécuter les cellules dans l'ordre : bootstrap → collecte → nettoyage → harmonisation → consolidation → export → QC
4. Livrable : `data/processed/dataset_final.csv` + docs (glossaire, dictionnaire)
