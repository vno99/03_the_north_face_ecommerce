---
title: Projet The North Face ecommerce
pinned: false
---

# Projet The North Face ecommerce

## Description du Projet

The North Face, une entreprise spécialisée dans les vêtements et équipements de plein air.
Le service marketing souhaite améliorer les taux de conversion grâce à d'un système de recommandation et redéfinir la structure de leur catalogue produit.

## Objectifs

* Identifier des groupes de produits
* Concevoir un algorithme de recommandation
* Topic Modeling pour évaluer les thèmes présents dans les descriptions

## Données

sample-data.csv: Dataset des descriptions de produits
500 lignes, 2 colonnes

## Structure du projet

* ```data/```: Jeux de données
* ```images/```: Images utilisées dans les notebooks
* ```notebook/```: Notebooks Jypiter

## Librairies Python
```
python -m pip install -r requirements.txt
```

## Installation du modèle de langue
```
python -m spacy download en_core_web_sm -q
```

## GitHub

https://github.com/vno99/03_the_north_face_ecommerce