
# Projet - AXA

Projet avec un nodejs en back et du html en front. Pour démarrer le projet
démarrer l'api en nodejs sous docker via :



## Copie env

Copier dans un nouveau ficher .env le contenu du fichier .env.exemple
## Installation API via Docker

Pour déployer l'api facilement lancer les commandes Docker ci-dessous :

```bash
  docker build -t api-axa .
```
```bash
  docker run -d -p 3000:3000 api-axa
```
L'api est disponible sous le port 3000


## Accéder à l'application

Rendez-vous dans le dossier front et ouvrer le fichier index.html dans votre navigateur
