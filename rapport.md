Nom et Prenom : AMRIOUI SARA

Adresse : saraamrioui146@gmail.com 



### Indice 1 ###
cd tresor_shell
# on utilise cd pour se déplacer dans le répertoire "tresor_shell"

./generer_probleme.py 16377
# on utilise cette commande pourexécuter le script python "generer_probleme.py"qui se trouve dans le repertoire actuel 

mkdir indices_sauvgarde
# on créé un nouveau répertoire nommé "indices_sauvgarde"

cat indices/12345/indice 
# la commande cat va nous permettre d'afficher le contenu du fichier "indice"

cp indices/12345/indice indices_sauvgarde/indice2
# on utilise cette commande pour afficher le contenu d'indice 2

### Indice 2 ###
cd /usr 
# on se déplace vers le répertoire "\usr" du système d'exploitation 

ls -l |wc -l 
# on affiche le nombre de fichiers et de répertoire dans le répertoire actuel

13
# on a trouvé 13 cela correspond à 12 sous répertoire plus lui meme 

cd ~/tresor_shell 
# on change le répertoire actuel du terminal pour le répertoire "tresor_shell" dans le répertoire personnel de l'utilisateur en cours  

./indice_suivant.py 3 12
28983 
# l'emplacement du prochain indice qui est indices/28983

cp indices/28983/indice indices_sauvgarde/indice3
# on utilise cette commande pour afficher le contenu d'indice 3

### Indice 3 ###

hostname 
# il m'a renvoyé "armstrong" qui le nom du l'ordinateur 

./indice_suivant.py 4 armstrong
72308
# l'emplacement du prochain indice qui est indices/72308

 cp indices/72308/indice indices_sauvgarde/indice4
 # on utilise cette commande pour afficher le contenu d'indice 4


### Indice 4 ###

man mv 
# pour lire le manuel de la commande mv 
-n 
# pour eviter l'ecrasement 

./indice_suivant.py 5 -n       
90260
# l'emplacement du prochain indice qui est indices/90260

cp indices/90260/indice indices_sauvgarde/indice5
# affichage du contenu de d'indice 5

### Indice 5 ###

cd  /comptes/a/as112323/tresor_shell
# on se deplace vers le répertoire "tresor_shell" situé dans le chemin "/comptes/a/as112323"

ls -al
 cd .cachette 
 cat .baobab 
616464

 cd ~/tresor_shell 
./indice_suivant.py 6 616464
23500
# l'emplacement du prochain indice qui est indices/23500

cp indices/23500/indice indices_sauvgarde/indice6
# affiche le contenu d'indice 6

### Indice 6 ###

echo $PATH
# En exécutant cette commande, on aura une liste de chemins de recherche pour les programmes exécutables sur notre système, qui sont séparés par des deux-points (:). Chaque chemin est un répertoire dans lequel le système d'exploitation recherche des programmes exécutables

/users/etudiant/a/as112323/bin:/usr/local/bin:/bin:/usr/bin:/usr/bin/X11:.
# le résulta du commande précedente 


./indice_suivant.py 7 /users/etudiant/a/as112323/bin
02759
# l'emplacement du prochain indice qui est indices/02759

cp indices/02759/indice indices_sauvgarde/indice7
# affiche le contenu d'indice 7

### Indice 7 ###

cd images
# on se déplace vers le répertoire "images"

tail -n 5 ecureuil.jpg:

 # le message affiché :
 La courbe de tes yeux fait le tour de mon coeur
Un rond de danse et de douceur
Auréole du temps, berceau nocturne et sûr
Et si je ne sais plus tout ce que j’ai vécu
C’est que tes yeux ne m’ont pas toujours vu

# L'indication vers l'indice 8 est formé à partir du dernier mot de chacune de ces lignes pour le fichier "ecureuil.jpg".

![Image de la ecureuil](ecureuil.jpg)


 
cd ..
# commande nous permettra de remonter d'un niveau dans la hiérachie des répertoires à partir du répertoire actuel

./indice_suivant.py 8 coeur douceur sûr vécu vu
43864
# l'emplacement du prochain indice qui est indices/43864

cp indices/43864/indice indices_sauvgarde/indice8
# affiche le contenu d'indice 8

### Indice 8 ###

touch toutpuissant.txt  
 echo " Je veux utiliser sudo.">>toutpuissant.txt 
 echo"AS">>toutpuissant.txt 
 # Création du fichier 'toutpuissant.txt' qui contient le texte
     Je veux utiliser sudo.
     AS

 sudo mv toutpuissant.txt /usr/local
 # Ondéplace le fichier 'toutpuissant.txt' dans le répertoire '/usr/local'
# il me demande le mot de pass du coup l'indication est impossible 

./indice_suivant.py 9 impossible 
45843
# l'emplacement du prochain indice qui est indices/45843

cp indices/45843/indice indices_sauvgarde/indice9
# affiche le contenu d'indice 9

### Indice 9 ###

ou Cherche a trouvé indice 10

 ls /usr/share/dict/
 wc -w ~/usr/share/dict/words
 # la commande nous retoutrne le nbr de mots dans le dictionaire :102401

./indice_suivant.py 10 102401

cp indices/97027/indice indices_sauvgarde/indice10
# affiche le contenu d'indice 10

### Indice 10 ###

grep -B 1 koala /usr/share/dict/words 

# le mot qu'on cherche ici c'est knuckling c'est elle qui apparait avant koala 

./indice_suivant.py 11 knuckling
80484 
# l'emplacement de notre prochain indice 

cp indices/80484/indice indices_sauvgarde/indice11
# affiche le contenu d'indice 11

### Indice 11 ###

ls -la /bin/ | sort -r 
# affichage de la liste des fichiers triés selon leur taille et la commande sort -r est l'option recherché

./indice_suivant.py 12 -r
20276
#  l'emplacement de notre prochain indice 

cp indices/20276/indice indices_sauvgarde/indice12
# affiche le contenu d'indice 12



### Indice 12 ###

find . -size -1452c 
# elle renvoie  
./indices/64857/indice

cat indices/64857/indice
# cette commande nous permettrons d'afficher le contenu du "indice" qui est dans "indices/64857"

cp indices/64857/indice indices_sauvegarde/indice13
# affiche le contenu de d'indice 13


/                                         \
|          🎉 Félicitations ! 🥳           |
\                                         /
 ----------------------------------------- 
  \                           .       .
   \                         / `.   .' " 
    \                .---.  <    > <    >  .---.
     \               |    \  \ - ~ ~ - /  /    |
         _____          ..-~             ~-..-~
        |     |   \~~~\.'                    `./~~~/
       ---------   \__/                        \__/
      .'  O    \     /               /       \  " 
     (_____,    `._.'               |         }  \/~~~/
      `----.          /       }     |        /    \__/
            `-.      |       /      |       /      `. ,~~|
                ~-.__|      /_ - ~ ^|      /- _      `..-'   
                     |     /        |     /     ~-.     `-. _  _  _
                     |_____|        |_____|         ~ - . _ _ _ _ _>







