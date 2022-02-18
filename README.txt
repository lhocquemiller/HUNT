Ce git est pour le dossier Content/Hunt, lequel doit évoluer avec le projet.
Je vous invite à faire vos modifications uniquement dans Content/Hunt, le reste du projet étant donc statique. Par exemple: si vous récupérez du contenu sur internet ou sur l’UE market place, rangez-le dans la hiérarchie du dossier “Content/Hunt”. TOUT doit pouvoir se trouver dans “Content/Hunt”.

Pour commencer:

Télécharger l’unreal engine. Version 4. (4.27)
Copier coller le projet entier qui se trouve sur le Google Drive, pour ensuite l’ouvrir avec l’UE.
Pour tester le jeu il faut ouvrir la carte “MainMenuLevel” qui se trouve dans Content/Hunt/Maps.
Par défaut, c'est un autre menu qui est ouvert.
Une fois le bon menu ouvert, l'écran est noir et vous pouvez jouer avec le bouton "Play".
Le gros du développement va se passer dans le dossier Content/Hunt. Ce dossier est donc hébergé sur un Git.
Pour profiter de la dernière version du jeu il vous faut le dernier dossier “Content/Hunt.”
Supprimez le dossier “Hunt” dans le dossier “Content” et téléchargez avec Git le dernier dossier “Hunt”.
La commande git est la suivante: “git clone https://github.com/lhocquemiller/Hunt.git”.
Il faut l'éxécuter dans une invite de commande dans le dossier "Content".
Vous remplacez ainsi le dossier Hunt par la version dev.
Avant de travailler sur le projet, veuillez créer une branche sur le git dans le cas où vous modifierez le dossier “Content/Hunt”. Si vous voulez modifier un autre fichier qui ne se trouve pas dans “Content/Hunt” alors prenez contact avec moi, il faudra changer les fichiers dans le Google Drive.


HORRIBLE BUGS:
1) My AI is running on place but does not move => This is a navmesh issue. Create a new nav mesh.