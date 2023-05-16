# Redirections d’entrées/sorties
Maîtriser les combinaisons de commandes à l’aide des redirections.

## Exercice 1 : 

### Solution : ### 

1. Avec la commande ``cat``, affichez le fichier ``.bash_history`` en le redirigeant vers le fichier ``my_hist.txt``.

```
$ cat .bash_history > my_hist.txt
```

2. Affichez le fichier ``toto`` (qui n’existe pas!) pour le rediriger vers le fichier ``fic1.txt`` puis consultez le fichier ``fic1.txt``.

```
$ cat toto > fic1.txt
$ cat fic1.txt
$ ls –l fic1.txt
```

3. Affichez le fichier ``toto`` (qui n’existe pas !) pour le rediriger vers le
fichier ``fic1.txt`` tout en redirigeant les erreurs vers ``fic2.txt`` puis consultez les fichiers ``fic1.txt`` et ``fic2.txt``.

```
$ cat toto > fic1.txt 2> fic2.txt
$ cat fic1.txt fic2.txt
$ ls –l fic1.txt fic2.txt
```


