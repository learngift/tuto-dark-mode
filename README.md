Tuto inspiré par git clone https://github.com/jdwilkin4/Light-Dark-Theme-Starter-Code.git

  mkdir tuto-dark-mode
  cd tuto-dark-mode

ajout du README.md, du .gitignore qui contient
/node_modules
/build
*.log*

on crée le fichier package.json :

  npm init -y
  npm i react react-dom react-scripts

Je n'aime pas trop react-scripts qui fait beaucoup de magie. Cela appelle webpack, modifie le fichier index.html. Le point d'entrée, c'est src/index.js

une manière plus pro est d'utiliser
npx create-react-app tuto-dark-mode --template typescript
La liste des templates se trouve sur la page
https://www.npmjs.com/search?q=cra-template-*%20react%20typescript

Par rapport aux templates courants, je pense le plus grand bien de esbuild (https://esbuild.github.io/getting-started/#your-first-bundle)

On commence avec une appli minimum pour avoir un premier état stable et faire un premier commit.



git init .
git add ...
git commit -m "..."
git remote add origin git@github.com:learngift/tuto-dark-mode.git
git push -u origin master
