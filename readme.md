Ce projet a été réalisé grâce à l'utilisation du préprocesseur Sass.

Pour installer Sass via Npm:

1.Récuperez et installez la dernière version de NODE.JS disponible sur https://nodejs.org/en/

2.Lancez l'invite de commmande windows.
Tapez :  node -v
cela vous permettra de verifier que Node est bien installlé et quelle est sa version
Tapez : npm -v
cela vous permettra de verifier que Npm est bien installlé et quelle est sa version

3.Dans VsCode ouvrez le terminal.
Les instructions suivantes sont entrées dans le terminal.

4.Tapez : npm package.json
Cela initiera le fichier .json qui permettra de lancer des scripts

5.Tapez : npm init
Cela vous permettra de crééer et configurer les informations du fichier .json

6.Installlez Sass en tapant : npm install -g sass
Vous pouvez vérifier la version de Sass en tapant : sass --version

7. Vous pouvez lancez vos scripts en les inscrivant dans le fichier package.json. Le script de ce projet est:

{
  "name": "writting-sass",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "sass": "sass --watch ./sass/main.scss:./css/style.css"
  },
  "author": "",
  "license": "ISC"
  }

Ce script permet de compiler les informations codées dans le fichier main.scss vers le fichier style.css

8.Pour lancer ce script, tapez : npm run sass