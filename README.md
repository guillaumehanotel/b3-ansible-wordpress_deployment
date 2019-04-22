# Projet Ansible - Déploiement Wordpress
Par Guillaume HANOTEL

Le projet consiste à déployer un site wordpress sur un Cloud Provider avec 1 serveur de base de données et 1 serveur web.

Ici le projet ne fonctionne que sur 1 machine car la liaison avec le serveur de base de données ne fonctionnait pas.

Le projet a été réalisé avec Ubuntu 18.04

Pour le faire fonctionner, renseignez votre IP public dans le fichier `host_vars/web01.yml` et lancez le playbook : 

``ansible-playbook plays/play-lamp.yml``

Rendez vous ensuite dans votre navigateur et rentrez votre IP dans l'URL. Vous serez redirigés vers l'interface de configuration de Wordpress.
