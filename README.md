Thibaut_ — Aujourd’hui à 08:01
**Nom    :** Hautot Sarah
**Groupe :** A1
**Année  :** 2023
**IUT Le Havre - Cours GIT**


Afficher plus
TP1.md
3 Ko
**Nom    :** Hautot Sarah
**Groupe :** A1
**Année  :** 2023
**IUT Le Havre - Cours GIT**


Afficher plus
TP2.md
5 Ko
**Nom    :** Hautot Sarah
**Groupe :** A1
**Année  :** 2023
**IUT Le Havre - Cours GIT**


Afficher plus
TP3.md
2 Ko
@Eléonore t'es vivante ?
Eléonore — Aujourd’hui à 08:06
Oui oui, j'arrive
Thibaut_ — Aujourd’hui à 10:05
https://drive.google.com/drive/folders/1W6LWAmW3EuVDjdYGx2sWBZceBx8JBFJX?usp=sharing
gameur002 — Aujourd’hui à 14:19
Pour faire les compte rendu du TP3 et TP4 : https://docs.google.com/document/d/13IeHuPlfp5Y1NqTEJbW6saEV1dWe0bGYBaJHdnO95LU/edit?usp=sharing
Google Docs
compte rendu TP3 et 4
gameur002 — Aujourd’hui à 15:26
on pourra les mettres dans les README.md
Thibaut_ — Aujourd’hui à 18:29
Vous vous couchez à quel heure
Eléonore — Aujourd’hui à 18:30
22
Thibaut_ — Aujourd’hui à 18:30
Ok
Ça vous vas 20h chez moi ?
On est pas encore revenu de la salle mdr
Eléonore — Aujourd’hui à 18:33
Oui, c'est bon pour moi
gameur002 — Aujourd’hui à 18:34
ok
Thibaut_ — Aujourd’hui à 18:36
Super nickel
gameur002 — Aujourd’hui à 19:11
C'est quelle numéro de ton appartement?
Thibaut_ — Aujourd’hui à 19:46
310
gameur002 — Aujourd’hui à 19:46
oki
Thibaut_ — Aujourd’hui à 19:47
Si vous êtes près tt les deux go venir plus tôt comme ça on finis plus tôt
Thibaut_ — Aujourd’hui à 20:00
@Eléonore t'es là?
Eléonore — Aujourd’hui à 20:01
J'arrive
Thibaut_ — Aujourd’hui à 20:01
okay
Eléonore — Aujourd’hui à 20:06
> **Nom :** BOULOCHE Eléonore
>
> **Groupe :** A
>
> **Année :** 1ère
>
> **IUT Le Havre - Cours GIT**

### Compte-rendu TP1 Introduction GIT


Dans ce TP on apprend à  travailler avec git.


# **Section 1 : Configuration de GIT**

Dans un premier temps, nous allons utiliser la commande `git config --list`, qui nous permet d'obtenir les informations concernant notre git.

## **Votre identité**

Après avoir vérifié ces informations, nous allons définir notre nom d'utilisateur et notre adresse mail :
```
git config --global user.name "Bouloche Eléonore"
git config --global user.email boulocheeleonore28@gmail.com
```

## **Votre éditeur**

Ensuite, nous allons renseigné l'éditeur de texte que nous souhaitons utiliser pour git :
```
git config --global core.editor visual studio code
```


Maintenant, nous allons nous assurer que les informations fournies sont correctes, à l'aide de la commande `git config --list`.
Afin de nous faciliter la tâche, nous allons utiliser les commande suivantes :
```
git config user.name
git config mail.user
```
Ces commandes vont nous renvoyer notre nom d'utilisateur et l'adresse mail que nous avons renseigné.



# **Section 2 : Création d'un dépôt git sur une machine locale**

Dans un premier temps, nous allons créer un répertoire nommer *courseGIT*, puis un sous-répertoire, que nous nommerons *tp1*.

La commande `tree courseGIT` nous renvoie les dossiers et fichiers que contient le dossier **courseGIT**.

Nous allons créer noter premier dépôt git via la commande `git init`.

## **La commande git status**

Afin de nous assurer que les modifications ont bien été enregistrées, nous allons utiliser la commande `git status`.



# **Section 3 : Création d'un fichier texte README.md**

Un fichier README.md est un fichier au format markdow. Nous allons l'enregistrer dans le dossier *tp1*.

## **Gérer les différentes modifications du fichier README.md**

Nous allons ajouter à notre git notre fichier *README.md*. Pour ce faire, nous allons utiliser la commande suivante : `git add README.md`. La commande `git add nom_fichier` permet de garder une trace des modifications antérieures.

Ainsi, lorsque nous taperons la commande `status`, nous obtiendrons le résultat suivant :
```
$:> git status
    ...

    new file: README.md
```

Ensuite, nous allons ajouter notre fichier dans noter dépôt git :
```
git add README.md
```

Enfin, nous allons vérifier que ce dernier à bien été ajouter :
```
$:> git status
On branch master
nothing to commit, working directory clean
```

Nous pouvons ainsi :
- Modifier ou créer un fichier
- Voir les fichiers à inclure dans le dépôt git
- Sélectionner puis enregistrer ou valider les changements dans le dépôt
- Voir les différentes version d'un fichier : `git log`

## **Différencier 3 états / 3 zones / 3 actions**

Nous allons mettre à jour le fichier *README.md*, dont voici les étapes :
- `git add README.md`           → ajout du fichier *README.md*
- `git commit -m "Version finale du compte-rendu"`  → enregistrement du fichier *README.me* dans le dépôt
- `git status`                  → vérification du status de notre dépôt

Nous obtenons alors le résultat suivant :
... (62 lignes restantes)
Réduire
README.md
7 Ko
gameur002 — Aujourd’hui à 20:16
**Nom : GIROMELLA Hugo

**Groupe : A1

**Année : 1er année

Afficher plus
README.md.txt
1 Ko
**Nom : GIROMELLA Hugo

**Groupe : A1

**Année : 1er année

Afficher plus
README.md.txt
1 Ko
Thibaut_ — Aujourd’hui à 20:33
Image
﻿
> **Nom :** BOULOCHE Eléonore
>
> **Groupe :** A
>
> **Année :** 1ère
>
> **IUT Le Havre - Cours GIT**

### Compte-rendu TP1 Introduction GIT


Dans ce TP on apprend à  travailler avec git.


# **Section 1 : Configuration de GIT**

Dans un premier temps, nous allons utiliser la commande `git config --list`, qui nous permet d'obtenir les informations concernant notre git.

## **Votre identité**

Après avoir vérifié ces informations, nous allons définir notre nom d'utilisateur et notre adresse mail :
```
git config --global user.name "Bouloche Eléonore"
git config --global user.email boulocheeleonore28@gmail.com
```

## **Votre éditeur**

Ensuite, nous allons renseigné l'éditeur de texte que nous souhaitons utiliser pour git :
```
git config --global core.editor visual studio code
```


Maintenant, nous allons nous assurer que les informations fournies sont correctes, à l'aide de la commande `git config --list`.
Afin de nous faciliter la tâche, nous allons utiliser les commande suivantes :
```
git config user.name
git config mail.user
```
Ces commandes vont nous renvoyer notre nom d'utilisateur et l'adresse mail que nous avons renseigné.



# **Section 2 : Création d'un dépôt git sur une machine locale**

Dans un premier temps, nous allons créer un répertoire nommer *courseGIT*, puis un sous-répertoire, que nous nommerons *tp1*.

La commande `tree courseGIT` nous renvoie les dossiers et fichiers que contient le dossier **courseGIT**.

Nous allons créer noter premier dépôt git via la commande `git init`.

## **La commande git status**

Afin de nous assurer que les modifications ont bien été enregistrées, nous allons utiliser la commande `git status`.



# **Section 3 : Création d'un fichier texte README.md**

Un fichier README.md est un fichier au format markdow. Nous allons l'enregistrer dans le dossier *tp1*.

## **Gérer les différentes modifications du fichier README.md**

Nous allons ajouter à notre git notre fichier *README.md*. Pour ce faire, nous allons utiliser la commande suivante : `git add README.md`. La commande `git add nom_fichier` permet de garder une trace des modifications antérieures.

Ainsi, lorsque nous taperons la commande `status`, nous obtiendrons le résultat suivant :
```
$:> git status
    ...

    new file: README.md
```

Ensuite, nous allons ajouter notre fichier dans noter dépôt git :
```
git add README.md
```

Enfin, nous allons vérifier que ce dernier à bien été ajouter :
```
$:> git status
On branch master
nothing to commit, working directory clean
```

Nous pouvons ainsi :
- Modifier ou créer un fichier
- Voir les fichiers à inclure dans le dépôt git
- Sélectionner puis enregistrer ou valider les changements dans le dépôt
- Voir les différentes version d'un fichier : `git log`

## **Différencier 3 états / 3 zones / 3 actions**

Nous allons mettre à jour le fichier *README.md*, dont voici les étapes :
- `git add README.md`           → ajout du fichier *README.md*
- `git commit -m "Version finale du compte-rendu"`  → enregistrement du fichier *README.me* dans le dépôt
- `git status`                  → vérification du status de notre dépôt

Nous obtenons alors le résultat suivant :
```
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
```



# **Section 4 : Gestion de version d'un programme Java**

Pour commencer, nous allons créer un répertoire *src* dans *tp1*. Dans ce dernier, nous allons créer notre programme java, à l'aide de la commande `touch Cryptomonnaie.java`.

Nous allons enregistrer ce premier programme java dans notre dépôt :
- `git add Cryptomonnaie.java`
- `git commit -m "Première version du fichier Cryptomonnaie.java`
- `git status` → le message est correct, le fichier java a été enregistré correctement, nous pouvons passer à la suite

En utilisant la commande `git log`, nous obtenons les informations qui suivent :
```
commit c7e023fd4547854e4b2d12ba1278de014353de71
Author: blc_ele <boulocheeleonore28@gmail.com>
Date:   Tue Apr 11 06:44:26 2023 +0200

    Première version du fichier Cryptomonnaie.java

commit 1f52bc421ca8200e894f5b94eab0fe76ad0ac3c1
Author: blc_ele <boulocheeleonore28@gmail.com>
Date:   Tue Apr 11 06:39:08 2023 +0200

    Ajout du fichier README.md
```

Nous obtenons les informations suivantes : 
- Le fichier *README.md* a été enregistré le 11 avril
- Le fichier *Cryptomonnaie.java* a été enregistré le 11 avril

## **Création du fichier .gitignore**

Lorsque nous compilons un fichier java, le fichier `.class` qui sera généré apparaîtra dans la zone de copie de travail. Nous pouvons le voir par la commande `git status`.

Afin d'éviter que ces fichiers ne soient enregistrés git, nous devons créer un fichier *.gitignore* dans le répertoire *tp1*.

Dans ce fichier, nous allons y ajoutez la ligne `*.class`. L'on peut en déduire que ce fichier va permettra de dire à github les fichiers générés automatiquement qu'il ne doit pas prendre en compte. 

Nous allons ensuite effectuer les commandes suivantes dans git :
- `git add .gitignore`
- `git commit -m ".gitignore ajouté"`

Désormais, lorsque nous tapons la commande `git status`, les fichiers `.class` n'apparaissent pas.

Nous allons ensuite ajouter les autres extensions : `.jar`, `.war`, `.nar`, `.ear`, `.zip`, `.tar.gz` et `.rar`. Ensuite, nous allons effectuer une nouvelle fois pas les commandes git :
- `git add .gitignore`
- `git commit -m ".gitignore modifié"`

Puis, nous allons terminer par la commande `git status` pour nous assurer que le fichier *.gitignore* a bien été modifié.
README.md
7 Ko
