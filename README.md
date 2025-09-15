# Rapport de stage — Papier

Ce dépôt contient les analyses Quarto (.qmd) et la structure du projet.

## Structure
- analyse_52/ : scripts Quarto (.qmd) par étape (ARIMA, BSTS, GAMM, etc.)
- biblio/ : bibliographie (BibTeX/CSL/notes)
- data/ : données (non versionnées) — voir data/README.md
- delivrables/ : documents finaux (PDF/présentations)
- resultats/ : sorties légères finales — voir resultats/README.md

## Reproduire l'environnement R
1. Dans R :
   install.packages("renv")
   renv::restore()

## Rendu des documents Quarto
1. Depuis la racine du projet :
   quarto render analyse_52

## Données
Les données ne sont pas versionnées. Place-les dans data/ comme indiqué dans data/README.md.
