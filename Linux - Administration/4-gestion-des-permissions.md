# Gestion des permissions

## Exercice 1 : 

### But : ### 
Savoir manipuler les propriétés et les droits des fichiers et des répertoires.

1. Donnez et expliquez les droits du fichier ``.bashrc`` situé dans votre répertoire *home*.

2. Dupliquez le fichier ``.bashrc``, renommez le en ``fichier1`` puis changez ses droits d'accès pour empêcher la lecture pour les utilisateurs « **autres** ».

3. Expliquez les notations suivantes
 - notation ``755``.
 - notation ``700``.
 - notation ``640``.
 - notation ``440``.

**Note** : Rappel r=4, w=2 et x=1

4. Modifier les permissions de votre répertoire personnel pour autoriser
l’accès aux utilisateurs « autres » (n’étant pas du groupe
ou propriétaire).
    
    Modifier les permissions de votre répertoire personnel pour interdire
l’accès à la catégorie des utilisateurs « autres ».

5. Modifiez le propriétaire du fichier ``fichier1`` à « **bin** ».
    
    Modifiez le groupe du fichier ``fichier1`` à « **daemon** ».
    
    Vérifiez avec la commande ``ls`` le propriétaire et le groupe du fichier ``fichier1``.
    
    Remettre le fichier ``fichier1`` avec le propriétaire et le groupe  original (``techno.techno``).
