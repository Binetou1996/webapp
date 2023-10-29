# webapp

Ce projet vous permet de déployer un site web statique avec Nginx dans un conteneur Docker.

## Prérequis

- Docker

## Instructions

1. **Clonez le dépôt**
   
   ```bash
   git clone https://github.com/Binetou1996/webapp.git
   cd webapp

2. **Construisez l'image Docker**

   ```bash
   docker build -t webapp-nginx .

3. **Exécutez le conteneur Docker**

   ```bash
   docker run -d -p 80:80 webapp-nginx

4. **Accédez au site web**

Ouvrez votre navigateur et accédez à http://localhost.

## Fonctionnalités

- Utilisation de ubuntu:18.04 comme image de base.
- Installation automatique de nginx et git.
- Déploiement automatique d'un site web statique depuis un dépôt GitHub.

## Auteur

- Binetou1996
