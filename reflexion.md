1. Structure du projet Git

Le projet contient plusieurs branches : main, branch/paco, branch/cat et branch/cisse.
La branche cat a créé le fichier tp.md contenant l’ancien contenu du README.
Le fichier README.md liste désormais l’URL du repository ainsi que les noms des élèves.
Le .gitignore contient les fichiers à ignorer par Git.
On trouve aussi un fichier cells.h avec des structures et fonctions, ainsi qu’un main qui exécute le programme et produit l’affichage.

2. Différence entre git fetch et git pull

git fetch : récupère les changements du remote sans modifier la branche locale.

git pull : récupère et applique directement les changements dans ta branche locale.

Exemples :
Fetch → pour voir ce qui a changé sans modifier ton travail.
Pull → pour mettre ta branche à jour avant de continuer.

3. Différence entre git reset et git revert

git reset : modifie ou supprime des commits (réécriture de l’historique). Risqué sur une branche partagée.

git revert : crée un nouveau commit qui annule un commit précédent, sans casser l’historique.

Situation risquée pour reset :
Utiliser reset --hard sur une branche déjà poussée sur GitHub, car cela casse la synchro avec les autres.
