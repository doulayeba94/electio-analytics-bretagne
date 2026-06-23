# Electio Analytics Bretagne

## Contexte

Projet réalisé dans le cadre du MSPR Big Data du titre RNCP35584 "Expert en Informatique et Systèmes d'Information".

L'objectif est d'analyser l'influence des indicateurs socio-économiques sur les résultats électoraux et de construire un modèle prédictif permettant d'anticiper les tendances électorales à court terme.

---

## Objectifs

- Collecte de données électorales et socio-économiques
- Nettoyage et fiabilisation des données avec Dataiku DSS
- Construction d'un modèle décisionnel
- Réalisation d'analyses exploratoires (EDA)
- Mise en œuvre de modèles de Machine Learning
- Visualisation des résultats



## Technologies utilisées

- Dataiku DSS
- PostgreSQL
- Python
- Power BI
- Machine Learning
- Git / GitHub



## Architecture du projet

Sources Open Data
↓
Dataiku DSS
↓
Nettoyage & Transformation
↓
Analyse Exploratoire (EDA)
↓
Machine Learning
↓
Visualisation & Restitution


## Structure du dépôt

```text
electio-analytics-bretagne/
├── datasets/
├── dataiku/
├── modelisation/
├── visualisations/
├── soutenance/
└── README_images/
```

## Analyses réalisées

### Analyse descriptive

- Distribution du chômage
- Distribution du revenu médian
- Distribution du taux de pauvreté

### Analyse de corrélation

Variables étudiées :

- Taux de chômage
- Taux de pauvreté
- Revenu médian
- Nombre d'entreprises
- Résultats électoraux

### Analyse géographique

Comparaison Bretagne / Reste de la France.


## Machine Learning

Modèles testés :

- Régression Logistique
- Arbre de Décision
- Random Forest

### Résultats obtenus

- Accuracy : 75,6 %
- Precision : 46 %
- Recall : 45,2 %
- F1-score : 37,9 %


## Auteur

Abdoulaye BA

Master Expert en Informatique et Systèmes d'Information - EPSI Paris