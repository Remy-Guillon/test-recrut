Ceci est le repo des sources du test.

La methode d'installation est la suivante :
1. A partir de la ligne de commande se placer dans le dossier /drupal
1. Taper 'composer install'
2. Taper 'docker-compose up'
3. taper 'docker exec -it test-recrut_php bash' pour rentrer dans le container php et acceder à drush
4. Taper 'drush cim' pour importer les fichiers de configuration

En cas de disfonctionnement un dump de la base de donnée est disponible -> drush sql-cli < exportdb.sql

Accès admin
login : Dev
MDP: dKp96!Dj6gfs

