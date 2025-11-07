# gestionnaire-de-tache
TD React avec typescript pour la création applicatoin gestionnaire de tâches

Ce projet est conçu pour la séance d'introduction à TypeScript (TS), au gestionnaire de paquets npm, et à la chaîne d'outils de développement moderne. L'objectif est de comprendre le rôle du typage statique et la compilation TS vers JS.

# Prérequis
Assurez-vous que les outils suivants sont installés sur votre machine :

Node.js et npm : (Node Package Manager).

Vérification : Ouvrez votre terminal et tapez :

Bash

node -v
npm -v
Visual Studio Code (VS Code) : L'éditeur de code recommandé.

Git : Système de contrôle de version.

💻 Phase d'Installation et Configuration
Suivez ces étapes pour cloner le dépôt et configurer l'environnement de travail.

Étape 1 : Cloner le Dépôt
Ouvrez votre terminal ou invite de commande et clonez le dépôt Git :

Bash

git clone [URL_DE_VOTRE_DEPOT]
cd td-ts-seance2
Étape 2 : Installation des Dépendances
Nous avons besoin de TypeScript et de ts-node (pour exécuter le code TS directement).

Bash

# Installe toutes les dépendances listées dans package.json
npm install
Rappel : Cette commande crée le dossier node_modules et installe TypeScript et ts-node en tant que dépendances de développement.

Étape 3 : Initialisation de TypeScript
Cette commande génère le fichier de configuration tsconfig.json que nous utiliserons pour paramétrer la compilation.

Bash

npx tsc --init
