# Git

1. Branches & Remote 
- **git branch -m "Old_Name" "New Name"** : pour renommer une branche
- **git branch "Name"** : créée une branche
- **git clone** : pour récupéré le projet et de lier le remote
- **git remote** : permet de créer, afficher et de supprimer des connexions avec d'autres dépôts.
- **git switch -c "name"** : bascule et créé la chaine
- **git restore** : restaure le fichier jusqu'au dernier commit
- **git diff** : dernier changement depuis le commit


2. Ordre : 
- 1 **git init** : permet de convertir un dossier en un dépôt git.
- 2 **git add** : ajouter a la liste à commit
- 3 **git status** : pour voir ce qui à était fait
- 4 **git commit -m** : commit et donne une informations sur ce qui a était commit
- 5 **git push** : envoyer les fichiers

3. Avant chaque modification faire : 
- 1 **git pull** : récupére les fichiers

4. Vérifications de la branch : 
- 1 **git branch**  : regarde le nombre de branch

5. Option.
    - git log : affiche les commits et leur 'hash', et permet de voir la liste des commits.
    - git revert [hash] : pour créé un commit qui va annuler ce commit et permet d'éditer le message du commit.

    - git reset : annule le dernier commit.     
    - git show : permet d'afficher des informations détaillées sur un commit spécifique dans un dépôt git.

    - git cherry-pick : Pour appliquer sélectivement des commits d'une branche a une autre (ne pas cherry pick sur la même branche) (flags :--continue pour continuer & --abort : pour annuler & <hash-du-commit>)

    - git bisect bad : permet de marquez le commit comme mauvais.

    - git bisect good <commit> : permet de marquez le dernier commit connu sans bogue pour le marquer comme bon.

    - git bisect reset : sert a terminer le processus de bisectage une fois le commit fautif identifié.