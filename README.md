# memo-git
Créer du code sur VSCode (ou autre éditeur de code). 
Passer sur Git-Bash pour enregistrer les fichiers en local et leur donner un No de version. 
Paramètres [ ] sont optionnels. 
Paramètres < > sont obligatoires. <...> sont à remplacer par nom de fichier, ou email, ou... 
Langages interprêtés : on écrit code dans VSCode et la même chose est lue par le navigateur / langages compilés : application desktop, il y a plein de trucs entre le code source et l'affichage navigateur. 
Commit : état de notre repo à un moment donné que l'on veut sauvegarder 
!! PENSER TAB !! 


DEMARRER sur git/bash (retrouver un niveau de dossier qui nous va bien, pour travailler dedans) : 
$ cd /g/Mon\ Drive/
une fois qu'on est dans mon Drive faire cd pour aller dans les sous-dossiers : cd git puis cd projet puis cd cv-nathalie (per exp) 


FONCTIONS : 
$ = veut dire ligne de commande. Déjà affiché. 
git version = git --version => 2.31.1 (version de Git, pas des docs).
git = help.
enregistrer nom = git config --global user.name "Nathalie Changeux" 
enregistrer email = git config --global user.email "nathalie.changeux@lecampusnumerique.fr"


CREER NOUVEAU DOSSIER = mkdir hello-world
ALLER dans ce nouveau dossier = cd hello-world
iINITIALISER ce nouveau dossier = git init (est vide pour l'instant). 
ls = liste de ce qu'il y a dans "ce" directory. 
ls al = afficher les fichiers cachés. 
git status : vérifier où j'en suis, voir les modifs 
git add readme.txt = ajout dans hello-world du doc readme créé dans VSCode 
git commit -m "creation du fichier readme" = message qui précise ce que l'on vient de créer ou modifier 
git diff = voir les modifs avant (en rouge)/maintenant (en vert)
!! PENSER A CREER UN NOUVEAU REPO SUR GITHUB !! (façon de faire expliquée sur Github) (git remote add origin <URLFROMGITHUB> URL de mon compte-Github)


pwd =  nom du répertoire courant, où l'on est. 
git add chocolat.md (fichiers ajoutés ou modifiés)  /  git commit -m" (sauvegarde à l'intant T, avec message de ce qu'on vient de faire")  /  git push (pour "envoyer" à GitHub). 
PUSH = envoyer local vers distant  /  PULL = récup distant en local  -  git push origin master
git config --global user.username <USerNamE> = ajouter un nom d'utilisateur gitHub (ATT à la casse) 
.gitignore = dossier dans lequel on met les fichiers qu'on ne veut, qui nous gênent (ex : desktop.ini) 
cd = changer de directory. 
md = créer un repository. 
CTRL C = qd ça rame. 
touch readme.txt = pour créer doc txt qui s'appelle readme. 
cd .. = remonter d'1 niveau dans les dossiers. 

*** A COMPLETER ***
