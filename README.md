# Smash — Mini-rapport exploratoire

Projet d'analyse exploratoire réalisé avec Python dans le cadre du Jour 2.

## Objectif

Analyser les ventes de Smash afin d'identifier les principaux leviers de performance commerciale.

## Données

Le projet utilise trois tables :

- commandes
- clients
- produits

Les tables sont jointes à partir de `client_id` et `produit_id`.

Seules les commandes ayant le statut `Livrée` sont prises en compte dans le chiffre d'affaires.

## Analyses réalisées

1. Performance par ville
2. Performance et rentabilité par catégorie
3. Évolution mensuelle du chiffre d'affaires
4. Analyse des modes de paiement
5. Impact des remises
6. Valeur des clients par canal d'acquisition
7. Comparaison semaine / week-end

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Lancer le projet

```bash
pip install -r requirements.txt