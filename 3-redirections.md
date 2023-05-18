# Redirections d’entrées/sorties
Maîtriser les combinaisons de commandes à l’aide des redirections.

## Exercice 1 : 

### But : ### 
Savoir utiliser le principe de la redirection.

1. Avec la commande ``cat``, affichez le fichier ``.bash_history`` en le redirigeant vers le fichier ``my_hist.txt``.

2. Affichez le fichier ``toto`` (qui n’existe pas!) pour le rediriger vers le fichier ``fic1.txt`` puis consultez le fichier ``fic1.txt``.

3. Affichez le fichier ``toto`` (qui n’existe pas !) pour le rediriger vers le
fichier ``fic1.txt`` tout en redirigeant les erreurs vers ``fic2.txt`` puis consultez les fichiers ``fic1.txt`` et ``fic2.txt``.


## Exercice 2 : 

### But : ###
Savoir utiliser le principe de la redirection avec le pipeline.

1. Utilisez une redirection pour écrire dans le fichier ``users-with-bash.txt`` les lignes du fichier ``/etc/passwd`` contenant la chaîne « **/bin/bash** » sans distinction majuscule/minuscule.

2. Affichez le nombre de lignes du fichier ``users-with-bash.txt``.

3. Affichez le nombre de ligne du fichier ``/etc/passwd`` contenant la chaîne « **/bin/bash** » sans distinction majuscule/minuscule en une seule ligne de commande avec le pipeline.

## Exercice 3 : 

### But : ###
Savoir utiliser le principe de la redirection avec le pipeline. !!!!!!

1. Comptez le nombre de lignes vides du fichier ``.profile`` en utilisant ``grep`` et ``wc``.

2. Comptez le nombre de lignes vides du fichier ``.profile`` en utilisant ``grep –c``.

3. Comptez le nombre de lignes du fichier ``.bash_history`` commençant par une majuscule. Essayez de copier le fichier ``.bash_history``, le renommer en ``test.txt``, l'éditer en ajoutant des majuscules puis réessayer.

4. Comptez le nombre de lignes du fichier ``test.txt`` ne commençant pas par une majuscule.

5. Comptez le nombre de lignes du fichier ``test.txt`` commençant par un chiffre.


