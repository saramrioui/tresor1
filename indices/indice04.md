### Indice 4 : les grands mouvements ###

#### Organisons ####

Nous avons exploré les répertoires qui existent déjà sur l'ordinateur. Mais
qu'en est-il si nous voulons créer nos propres répertoires et fichiers ? Pour
commencer, créons un nouveau répertoire.

D'abord, allons dans le répertoire de la chasse au trésor :

    cd /comptes/a/as112323/tresor_shell

Ensuite, exécutons

    mkdir indices-sauvés

Nous allons sauvegarder tous les indices trouvés dans un répertoire séparé créé
au moyen de la commande `mkdir` (make directory). Comme le fichier README est
l'indice 1, nous n'avons pas à nous en préoccuper. Si vous avez noté les
emplacements des indices, la partie suivante devrait être facile.

#### Recopions ####

Copions tous les indices que nous avons trouvés dans le répertoire de
sauvegarde :

    cp indices/12345/indice indices-sauvés/indice2
    cp indices/28983/indice indices-sauvés/indice3

Cela copie (`cp`) chaque indice dans le nouveau répertoire et leur donne de
nouveaux noms. Si nous avions seulement exécuté

    cp indices/12345/indice indices-sauvés/
    cp indices/28983/indice indices-sauvés/

alors le second fichier aurait écrasé le premier, parce qu'ils portent le même
nom.

#### Gardons nos options ouvertes ####

Les commandes Unix ont souvent des options qui changent leur comportement. Par
exemple, comparer `ls -l` à l'ordinaire `ls`. Ici, `-l` est une option. On peut
grouper des options ensemble ainsi :

    ls -lahS

La meilleure façon de découvrir les options est la page de manuel.

#### Déplaçons ####

Disons que nous n'aimons pas le nom du répertoire `indices-sauvés`. On peut le
déplacer (renommer) avec `mv` :

    mv indices-sauvés [choisir un nouveau nom]

Exécutons alors `ls` pour voir les résultats du déplacement. Prudence avec
`mv` : on peut écraser un répertoire / fichier qui existe déjà ! 

#### Trouver l'indice 5 ####

Lire la page de `mv` et trouver une option qui empêche l'écrasement. Cette
option est votre prochaine indication.

