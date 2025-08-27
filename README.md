# 🏠 Laplace Immo – Analyse des transactions immobilières

## 📌 Contexte

Laplace Immo est un réseau national d’agences immobilières souhaitant :

- Centraliser les données sur l’ensemble des transactions immobilières en France.
- Suivre l’évolution du prix au m².
- Produire des analyses permettant de mieux comprendre le marché immobilier.
  
Ce projet est un POC (Proof of Concept) basé sur les données du premier semestre 2020 issues des valeurs foncières.

## 🗂️ Données et préparation

Sélection des colonnes pertinentes.

Création d’identifiants uniques (id_commune, id_vente, id_bien).

Mise en cohérence avec un schéma relationnel.

Bases construites :

- Bien : 34 169 lignes.
- Vente : 34 151 lignes.
- Commune : 34 991 lignes.

## 🔎 Analyses réalisées

Plusieurs requêtes SQL ont permis d’explorer le marché immobilier :

1. Nombre d’appartements vendus au 1er semestre 2020.
2. Répartition des ventes par région.
3. Proportion des ventes par nombre de pièces.
4. Les 10 appartements les plus chers au m².
5. Prix moyen au m² d’une maison en Île-de-France.
6. Top 10 des appartements les plus chers (avec surface et région).
7. Évolution du nombre de ventes entre T1 et T2 2020.
8. Classement des régions selon le prix au m² des appartements >4 pièces.
9. Communes avec au moins 50 ventes au T1.
10. Différence de prix au m² entre 2 pièces et 3 pièces.
11. Moyenne des valeurs foncières dans les principales communes de certains départements (06, 13, 33, 59, 69).
12. Top 20 des communes avec le plus de transactions rapportées à la population (≥10 000 habitants).

## 📈 Résultats principaux

Forte disparité régionale du prix au m² (avec un écart notable entre grandes métropoles et reste du territoire).

Confirmation du niveau élevé des prix en Île-de-France, notamment pour les maisons.

Mise en évidence de différences structurelles entre appartements de 2 et 3 pièces.

Détection des communes les plus dynamiques rapportées à leur population.

## 🚀 Perspectives

Pour enrichir le projet, plusieurs pistes ont été identifiées :

- Ajouter des variables comme la surface Carrez ou la surface de terrain pour les maisons.
- Étudier la relation entre la population et le prix au m². 
- Comparer l’évolution des ventes maisons vs appartements.
- Approfondir l’analyse sur les arrondissements de grandes villes (Paris, Lyon, Marseille).  
