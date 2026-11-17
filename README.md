# Projet d'analyse : ventes d'une boutique

Nettoyage, standardisation et analyse d'un jeu de données de ventes sous Excel, présentés dans un tableau de bord.

## Objectif
Transformer des données de ventes saisies de façon incohérente en une base fiable, puis identifier les mois, villes, catégories et modes de paiement qui rapportent le plus.

## Contenu
- `Projet_ventes_boutique.xlsx` : fichier principal

Le classeur contient 4 feuilles :

| Feuille | Rôle |
|---|---|
| **ventes_brut** | Données brutes (191 lignes), avec des formats incohérents |
| **Standardisation** | Données nettoyées et uniformisées (181 lignes), avec une colonne Mois ajoutée |
| **Analyse TCD** | Tableaux croisés dynamiques |
| **Visualisation et Dashboard** | Graphiques et tableau de bord final |

## Problèmes rencontrés dans les données brutes
- Dates dans plusieurs formats (`2026-05-15`, `19/03/2026`, `15 January 2026`)
- Prix et totaux écrits de différentes façons (`1 800 F`, `500 FCFA`, `3200`)
- Noms et villes avec des casses et espaces différents (`awa koné`, `Abidjan `, `bouaké`)
- Catégories et modes de paiement non uniformes (`ALIMENTAIRE`, `especes`, `Espèces`)

## Nettoyage réalisé
- Harmonisation des dates en un seul format
- Conversion des prix et totaux en valeurs numériques
- Correction de la casse et suppression des espaces superflus
- Uniformisation des catégories et des modes de paiement
- Suppression des lignes en trop (191 lignes brutes, 181 après nettoyage)
- Création d'une colonne **Mois** avec la fonction `TEXTE`

## Analyses réalisées
- Mois qui rapportent le plus
- Villes qui rapportent le plus, par catégorie de produit
- Répartition des ventes selon le mode de paiement
- Tableau de bord récapitulatif

## Outils utilisés
- Microsoft Excel : nettoyage de données, formules, tableaux croisés dynamiques, graphiques

## Aperçu
<img width="1207" height="536" alt="image" src="https://github.com/user-attachments/assets/6eb62c48-dac4-4516-be08-b18d0de41321" />


## Auteur
Senpai00225
wilfried.saw00225@gmail.com
