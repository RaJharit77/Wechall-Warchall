# WeChall Warchall

## Warchall - The beginning

## Level 0
Tout d'abord,  je suis rentré dans "Register" pour créer un compte de WeChall pour les challenges afin d'enregistrer mon parcours pendant les défis. Après j'ai réconfiguré mon ssh avec un message de succès de la configuration. Pour information, j'ai utilisé la terminale sur windows "invite de commande" pour connecter à mon compte ssh.
J'ai débuté par le commande "pwd", "ls" pour voir les contenus et j'ai trouvé un dossier "level" pour le challenge dans le dossier "home" ensuite j'ai commencé par le niveau 0.

--bash 

Sur mon terminale : ssh -p19198 user@warchall.net

user@warchall.net's password : ******

user@warchall:/home/level$ 

user@warchall:/home/level/00$ cat "nom_du_fichier".txt

--bash

## Level 1
L'utilisation de la commande grep pour rechercher un motif dans le fichier qui contient la solution sans y accèder directement.

--bash

user@warchall:/home/level/01$ grep -rn "solution" *

--bash

## Level 2
La solution est dans le dossier "./porb"
--bash

user@warchall:/home/level/02/.porb$ solution

--bash

## Level 3
J'ai utilisé la commande "cat"
--bash

user@warchall:/home/level/03$ cat .bash_history

--bash

## Level 4
La solution se trouve dans le dossier "level" principal et aussi dans le fichier ".md".

--bash

user@warchall:/level/04_kwisatz$ cat "solution".md 

--bash

## Level 5
La solution se trouve dans le fichier ".md"

--bash

user@warchall:/home/level/05$ cat "solution".md

--bash

## Level 12
J'ai modifié le fichier python puis j'ai accédée dans un dossier "tmp" ainsi que j'ai découvert la solution.

--bash

user@warchall:/tmp$ ./pytong ./check

--bash

## Level 14
J'ai modifié le lien de ce site web puis une fichier de code s'affiche sur la page en format ".php" après une code html de base 64 affiche la solution pour ce défi
dans la code source de la page.

--bash 

user@warchall:/home/level/14_live_fi/www/index.php$ cat "solution".php

--bash

## Level 15
J'ai modifié le lien de ce site web puis une fichier de code s'affiche sur la page en format ".php" après une code html de base 64 affiche la solution pour ce défi
dans la code source de la page.

--bash

user@warchall:/home/level/15_live_rfi/www/index.php$ <?php system(“cat solution.php”)?

--bash
