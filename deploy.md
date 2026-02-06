# Rapport de déploiement - BENAYAD
## Liens
- **Application en ligne :** https://rahmasca.osc-fr1.scalingo.io/
- **Dépôt de code :** https://github.com/Rahmab22/scalingo.git
## Prérequis techniques
PHP 8.4+
avec l'extension pdo_msql
Composer installé
Un compte
Scalingo
## Fichier de configuration CI
Le fichier de configuration de l'intégration continue se trouve dans :
.github/workflows/ci.yaml

## Procédure de déploiement pas à pas
1.Créer l'application
2.Ajouter l'add-on MySQL
1.Push des commits :
git push