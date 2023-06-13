# Tutoriel Mise en place de l'infrastructure Devops

## Description

Ce projet déploie un Wordpress en tant que front-end, une base de données MariaDB, un serveur de monitoring Portainer, un serveur phpmyadmin et un load balancing.

## Prérequis
- Avoir une machine.
- Docker doit être installé sur votre machine.

## Guide d'installation 
1. Ouvrez Docker Desktop sur votre machine ainsi qu'un cmd en mode administrateur.

2. Créer un dossier spécialement pour les fichiers à installer sur votre machine.

3. Installer le  **docker-compose**, **Dockerfile_front**, **haproxy.cfg** et **bdd.sql** qui se trouvent dans le dossier **devops** sur le github.

4. Faire **docker compose -f .\docker-compose.yml up** via le cmd dans le dossier où se situe vos deux fichiers. 

5. Attendre que tout soit mis en place. Constater que tous les containers ont été créé sur docker desktop.
 
6. Enfin pour se connecter aux différentes applications, utiliser **localhost:port** selon le port alloué par l'application.
