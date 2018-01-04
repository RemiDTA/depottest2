#Les commandes GIT :

git init : initialisation d'un git sur le repertoire courant

git status : permet de verifier le statut de notre git

git add file : ajoute le fichier file pour le prochain commit (possibilité d'utiliser "." pour dire d'ajouter tous les fichier)

git commit -m "version du projet" : commit avec l'option message

git log : affiche des informations sur les commit deja effectuer

git checkout num_commit fichier : permet de revenir a la version portant num_commit comme numéro d'id (ce numéro est obtenu grace a git log). Si on y mets un nom de fichier cela permet de recuperer que ce fichier.

git branch maBranche : créer une branche dans notre arborescence (on peut alors commit sur une branche qui se conduit comme un pointeur.

git push : commit mais sur le serveur distant (contrairement a commit qui ne mais a jour la version qu'en local)

git pull : permet de recuperer le projet du serveur distant jusqu'en local

git merge | git rebase : permet de fusionner un projet d'une branche sur une autre
