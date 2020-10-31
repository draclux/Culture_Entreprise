# Culture_Entreprise
Projet Cloud 2020

Ceci est un projet pour la matière Cloud infrastructures / Culture d'Entreprise.
Il est basé sur Docker. C'est un jeu fait python (un pong) qui tourne dans un conteneur et partage des fichiers avec un autre conteneur qui héberge un site web
affichant les scores des parties précédentes.

Pour lancer le projet, veuillez suivre les étapes:

1) Télécharger le projet (2 dockerfile et un fichier docker-compose.yml)

2) Ouvrir un terminal se trouvant dans le répertoire du projet.

3) NE PAS OUBLIER de taper la commande: xhost +   

4) Ensuite, taper la commande suivante: docker-compose up --build

5) Une fois les téléchargements terminés, vous avez normalement un pong de lancé sous les yeux. Si vous souhaitez fermer le jeu, cliquez sur la croix.

6) Vous pouvez accéder au site web via un navigateur à l'adresse suivante: localhost:8080

7) ATTENTION, si toute fois le site web n'affiche pas les scores, vous devez VIDER le CACHE du navigateur et recharger la page. J'ai noté que le site web 
fonctionnait mieux sous Firefox.
