# WINDMAP — Prospection éolienne Wallonie

Application web de prospection de sites éoliens en Wallonie : 990 sites candidats, scoring physique (vent + raccordement), probabilité de permis calibrée sur 488 arrêts du Conseil d'État, couches officielles SPW en direct, recherche par ville / adresse / parcelle cadastrale, cahier des charges téléchargeable en PDF.

## Déploiement
`index.html` est une application autonome (un seul fichier). Netlify la déploie telle quelle — aucun build nécessaire. À chaque `git push`, Netlify redéploie automatiquement.

## Données embarquées
990 sites scorés, 651 éoliennes existantes, 221 refus/annulations CE détaillés, 3 masques d'exclusion par classe d'éolienne. Les couches de contraintes (Natura 2000, captages, plan de secteur…), le géocodeur d'adresses et le cadastre sont appelés en direct au Géoportail wallon (connexion internet requise).

## Avertissement
Outil d'aide à la prospection — ne remplace ni étude d'incidences ni conseil juridique.
