`git config --list`   Lister config locale

`git status`

`git add *.txt`

`git commit -a -m` pas besoin de git add .

`git rm —cached file.txt`  retirer fichier uniquement du suivi

`git reset HEAD nom-du-fichier` retirer fichier de l’index ( annuler un git add )

`git config --global core.excludesfile ~/.gitignore_global` 

`git log`

`git commit —amend`   remplacer dernier commit fait par erreur (s’il a pas été push)

`git restore fichier1.txt`    annuler modifications non indéxées 

`git checkout id-commit mesinfos.txt`  ramène fichier d’ancien commit

`git reset --hard HEAD~1` Efface dernier commit et te remet sur celui d’avant

`git reset —soft HEAD~2` effacer 2 derniers commits mais laisse les fichiers

`git reset --hard id-Commit` efface les commits apres celui ci

`git reset --hard id-Commit~1` pareil mais avec lui compris 

soft : Apres git add 

mixed  : Avant le git  add 
`git revert id-commit` ajoute un commit qui annule le -ou les- commit spécifié

`git reflog` historique détaillé des commandes

`git branch nom-branche`  créer branche

`git checkout nom-branche`  pointer le head vers une branche

`git checkout -b nom-branche`  créer et pointer vers la branche

$ git branch -d <branch_name> // Supprimer la branche spécifiée,

 $ git branch –m old_name new_name // Renommer

`git merge nom-branche`  // Permet de merge une branche avec celle actuelle

`"git merge --squash` // fusionne une branche dans une autre branche sans créer de commit de fusion.

`git rebase nom-branche`  // Récupérer les modifications d’une branche

`git merge —abort` // Annule merge

git stash // Cacher travail effectué depuis dernier commit temporarirement

git stash list // lister stash 

git stash apply // Récupérer dernier stash 

git stash pop // Pareil mais l’efface de la stash list
