### Indice 5 : explorer en détail ###

#### Lister sans se déplacer ####

La commande `ls` permet de lister le contenu d'un répertoire. Si vous tapez

    ls

sans paramètre, vous listez le contenu du répertoire courant. Mais vous pouvez
aussi lister le contenu d'un répertoire sans vous déplacer

    ls /comptes/a/as112323/tresor_shell/images

permet ainsi d'obtenir le contenu du répertoire passé en paramètres.

#### Fichiers et dossiers cachés ####

Sous UNIX, les fichiers et répertoires dont le nom commence par un point sont
des fichiers cachés et ne sont pas visibles sauf si on le demande
explicitement. Taper

    ls -a

pour voir (aussi) les fichiers et répertoires cachés. Pour obtenir un affichage
détaillé de tous les fichiers, taper

    ls -al

ou encore

    ls -la

Pour plus de détails sur le fonctionnement de la commande `ls` et ses options,
vous pouvez consulter la page de manuel de `ls` : taper `man ls`

#### Trouver l'indice 6 ####

Dans le répertoire /comptes/a/as112323/tresor_shell, il y a une *cachette*, que vous
devriez explorer. En particulier, cherchez-y un fichier baobab. Vous
y trouverez l'indication vers le prochain indice.

Rappel : pour trouver l'indice suivant, tapez

    ./indice_suivant.py 6 [indication]

