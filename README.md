# projet-collectif---back-fraises

Backend part with Mehmet, Julie B, Juanita, Clementine and Delhia. Then switch Alex, Assetou, Faris and Julie D.

- Ce projet collectif à pour objectif de créer un site e-commerce en respectant certaine contraintes. Avec deux équipes: une front-end et une back-end. Projet sur deux semaines, une équipe travaillant sur une stack puis change la semaine d'après. 

## Notions abordées:

- Déploiement web
- Bases de données
- Interactions Front-end/Back-end
- Utilisation d’un framework pour le back-end

## Outils:

- React-Bootstrap/Nodejs
- Postman, MongoDB
- Slack, Notion, Miro

<p><img align="center" alt="" src="https://github.com/Alexluu13/P5_E-commerce-front-fraises/blob/main/p5_e-commerce_1.png"/></p>
<p><img align="center" alt="" src="https://github.com/Alexluu13/P5_E-commerce-back-fraises/blob/main/p5_e-commerce_5.png"/></p>
<p><img align="center" alt="" src="https://github.com/Alexluu13/P5_E-commerce-back-fraises/blob/main/p5_e-commerce_6.png"/></p>
<p><img align="center" alt="" src="https://github.com/Alexluu13/P5_E-commerce-back-fraises/blob/main/p5_e-commerce_7.png"/></p>

Le sujet du projet est de créer un site e-commerce à partir d'une commande client (Lauréline Fleury) et de respecter les demandes de cette dernière, c'est-à-dire: un site internet pour afficher ses produits, une page principale qui regroupera les meubles en vente, un encart dans lequel on pourra retrouver une photo, le type de meuble, le prix et un bouton pour l’acheter, accéder au détail du produit, une page admin... Pour les utilisateurs: ils pourront créer un compte (email + mot de passe), une page qui permet aux utilisateurs connectés de proposer des meubles à vendre...

Lancer Reactjs.
cd mon-app 
npm start

Lancer Nodejs.
npx nodemon server

Quitter un serveur. 
control + c

***
***

# Transition for the frontend team :

1. Install Nodejs (https://nodejs.org/en/download/)
2. Clone the repo git
3. run "npm install" to install all dependencies
4. Install nodemon, pretty useful if you don't want to relaunch you server, it will refresh it automatically

   npx install nodemon
   
   npx nodemon server

What we did for the setup (you don't have to do it again):

- Master to main: (short version, else see : https://pythonforundergradengineers.com/how-to-change-a-github-repo-from-master-to-main.html)

Clone the repo
git clone git@github.com:adatechschool/projet-collectif---back-fraises.git

git branch -m master main

git push -u origin main

git symbolic-ref refs/remotes/origin/HEAD refs/remotes/origin/main

# change default branch on GitHub

git push origin --delete master

- Next we install: node's modules and dependencies, mongoDB, express, CORS, dotenv...
  Prerequisites:
  Install NPM packages
  
  npm init -y
  
  npm install mongodb express cors dotenv
  
  You'll have the node_modules repo and two files, package-lock.json and package.json.
  Create a .gitignore file because you don't want all the node_modules files in git. This is the .gitignore template we used : https://github.com/github/gitignore/blob/main/Node.gitignore

- Creation of the server : server.js and app.js files
  You can check every GET and POST request with Postman
