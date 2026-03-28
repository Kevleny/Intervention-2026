# Notes de projet — Applications Compte Rendu

## Workflow de déploiement

À chaque modification d'un fichier HTML du projet, toujours suivre ce workflow :

1. Modifier le(s) fichier(s) HTML localement
2. Commit + push vers `Kevleny/Intervention-2026` (branche main)
3. Mettre à jour la base de données Supabase si le HTML concerné a des changements liés à la BDD (nouvelle table, nouvelle colonne, etc.)
4. Vérifier que le site en ligne fonctionne correctement et sans erreur

## Liens

- **GitHub** : https://github.com/Kevleny/Intervention-2026
- **Supabase** : https://ttuisauvkjqldkmejgtg.supabase.co
- **index.html** : https://kevleny.github.io/Intervention-2026/
- **TechLabApps-Desktop.html** : https://kevleny.github.io/Intervention-2026/TechLabApps-Desktop.html
- **rapport.html** : https://kevleny.github.io/Intervention-2026/rapport.html

## Base de données (tables)

- `interventions` — fiches d'intervention
- `techs` — techniciens
- `sites` — sites d'intervention
- `rapports` — comptes-rendus générés depuis rapport.html
