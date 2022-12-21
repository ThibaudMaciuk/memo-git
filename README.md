# memo-git


Commande apprise:

git checkout = positionnez le HEAD sur une branche specifique

	exemple : git checkout MAIN

git revert = annulez les modification d'une branche distante

	exemple : git revert MAIN

git reset = annulez les modification d'une branche locale

	exemple : git reset HEAD~1

git rebase = permet de rejoindre tout les commit d'une branche vers la fin de la branche cible

	exemple : git rebase BRANCHE_A_COMPLETEZ BANCHE_A_AJOUTER

git checkout HEAD^ = revenir au commit precedent

git checkout HEAD~2 = revenir 2 commit en arriere

git merge =  faire rejoindre les commit de la branche actuelle vers une branche cible
	exemple : git merge MAIN

git branch -d : supprimer une branche

	exemple : git branch -d Feature
