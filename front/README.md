# P13_Bank

## Author Pascal-Debailleul


Créer avec CRA (Create-React-App)

## Information générale

Création d'une application avec un système d'authentification pour une banque

---

## Prérequis

- Un éditeur de texte `VSCode, Vim, IntelliJ...`
- [Node.js < v.16](https://nodejs.org/en/)
- [Git](https://git-scm.com/)

---

- Lancement de l'application

```bash
npm run start
# ou
npm start
# avec Yarn
yarn start
```

- Installations des packages à la suite du clonage.

```bash
# avec NPM
npm install
# avec Yarn
yarn
```

## Dépendances ajoutées

 "@emotion/react": "^11.10.4",  
"@emotion/styled": "^11.10.4",  
"@mui/icons-material": "^5.10.3",  
"@mui/material": "^5.10.5",  
"@reduxjs/toolkit": "^1.8.5",  
"axios": "^0.27.2",  
"i": "^0.3.7",  
"prop-types": "^15.8.1",  
"react": "^18.2.0",  
"react-dom": "^18.2.0",  
"react-redux": "^8.0.2",  
"react-router-dom": "^6.3.0",  
"react-scripts": "5.0.1",  
"redux": "^4.2.0",  
"web-vitals": "^2.1.4"  

## Scripts ajoutés

En plus des scripts natif de CRA, il y a :

- `clean`     supprime les dossiers build, dist et docs.
- `clean:all` supprime les dossiers node modules et build, dist ainsi que le fichier package-lock.json.

## Back

[Lien Github](mettre le lien quand le reposite sera créé)

- Lire le README
- Veiller à bien lancer le back et le serveur.  

```bash
# Start local dev server
npm run dev:server

# Populate database with two users
npm run populate-db
```

Les routes Back sont disponible [ici => swagger](http://localhost:3001/api-docs/)
