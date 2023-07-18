# Git - Gitflow solo advanced

Le but de cet exercice est de maîtriser une utilisation plus avancée de `git` avec les branches.

Cette méthode est adaptée pour la conduite d'un projet en versions successives par un seul développeur avec un seul poste de travail.

## Étapes

D'abord :

- créez un nouveau dossier de projet (le nom du projet est libre)
- initialisez votre repo git local
- créez un repo git distant sur Github
- faites le lien entre votre repo local et le repo distant

Ensuite procédez aux étapes suivantes :

1. branche `master` : créez le fichier de documentation `README.md` et ajoutez du texte dedans
2. créez la branche `home`
3. branche `home` : créez le fichier html `index.html` et ajoutez du code dedans
4. branche `home` : modifiez le fichier html `index.html`
5. branche `master` : fusionnez en local (pas sur Github) la branche `home`
6. branche `master` : poussez la branche sur Github
7. créez la branche `contact`
8. branche `contact` : créez le fichier html `contact.html` et ajoutez du code dedans
9. branche `contact` : modifiez le fichier html
10. créez la branche `bugfix` en partant de la branche `master`
11. branche `bugfix` : modifiez le fichier html `index.html`
12. branche `master` : fusionnez en local (pas sur Github) la branche `bugfix`
13. branche `master` : poussez la branche sur Github
14. branche `contact` : rebasez votre branche sur la branche `master`
15. branche `contact` : modifiez le fichier html `contact.html`
16. branche `master` : fusionnez en local (pas sur Github) la branche `contact`
17. branche `master` : poussez la branche sur Github