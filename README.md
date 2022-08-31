# Projet demo express ts mongoose

Ce projet est destiné à l'apprentissage de mongoose

##Configuration

La configuration s'effectue via les variables d'environnements

Les voici :

| nom         | description                      | exemple de valeur |
| ----------- | -------------------------------- | ----------------- |
| SERVER_PORT | port sur lequel lancer le server | 3000              |

Il est possible de spécifier via un fichier env qui doit être crée à la racine.
Un exemple est disponible à la rcine du projet `env.exemple`

## Initialisation du projet : 

```bash
npm init 
tsc --init --location=global
npm i typescript
npm i express
npm i ts-node-dev mongoose @types/mongoose dotenv @types/express 
```
