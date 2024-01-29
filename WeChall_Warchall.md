# WeChall Warchall

## Warchall - The beginning

## Level 0
Tout d'abord, j'ai rentré dans le site web qui contient le sujet et je l'ai lu un peu. Après je suis rentré dans "Register" pour créer un compte de WeChall pour les challenges afin d'enregistrer mon parcours pendant les défis. J'ai suivi tous les instructions de création de compte. Après j'ai réconfiguré mon ssh puis il m'envoye mon compte ssh avec un message de succès de la configuration, je peux connecté à mon ssh depuis mon terminale. Pour information, j'ai utilisé la terminale sur windows "invite de commande" pour connecter au mon compte ssh.
J'ai débuté le challenge par la lecture du sujet, puis j'ai utilisé les commandes ls pour voir les contenus et j'ai trouvé un dossier "level" pour le challenge dans le dossier "home" et j'ai su que c'etait le défis ensuite j'ai débuté le challenge par les indications du sujet en commençant par le niveau 0.

--bash 

Sur mon terminale : ssh -p19198 user@warchall.net

user@warchall.net's password : ******

user@warchall : /home/level$ 

user@warchall : /home/level/00$ cat "nom_du_fichier".txt

--bash

## Level 1
L'utilisation de la commande grep pour rechercher un motif dans le fichier qui contient la solution sans y accèder directement
--bash

user@warchall : /home/level/01$ grep -rn "solution" *

--bash

## Level 2
La solution est dans le dossier "./porb"
--bash

user@warchall : /home/level/02/.porb$ solution

--bash

## Level 3
--bash

user@warchall : /home/level/03$ cat .bash_history

--bash

## Level 4
--bash

user@warchall : /level/04$ "solution".md 

--bash

## Level 5
--bash

user@warchall : /home/level/05$ cat "solution".md

--bash
