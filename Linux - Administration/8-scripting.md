# Scripting

## Exercice 1 : 

### But : ### 
Développer un script shell de complexité moyenne.
Le script affiche quelques informations de la machine à l’écran et génère une page « **html** » permettant de consulter ces informations avec un navigateur.

1. Écrire l’en-tête du script « **informations-machine** »
   - Appel de l’interpréteur ``bash``
   - Nom du script
   - Objet du script
   - Auteur du script
   - Date de création du script
   - Version du script (initialisez à ``1.0``)

2. Écrire la section des variables du script « **informations-machine** ».
   - Initialisez la variable ``ENCEMOMENT`` à la date et heure du jour.
   - Initialisez la variable ``TITRE`` avec le titre du script et le nom de la machine (utilisez la variable système ``$HOSTNAME``)
   - Initialisez la variable ``ENTETE`` avec « page developpee le » et la variable ``ENCEMOMENT``.

3. Écrire la boucle de saisie de l’opérateur qui permet l'affichage de la variable ``TITRE`` puis ``ENTETE``.

    Faites une boucle qui affiche les libellés suivants : « **Choix disponible** : ».
    
    [S] informations sur le systeme d’exploitation utilise.
    
    [R] informations sur les parametres reseau.

    [T] depuis quand le systeme fonctionne.

    [D] informations sur l’espace disque.

    [U] informations sur l’espace disque utilise par les usagers.

    [H] ecrire toutes ces informations vers informations-machine.html.

    [Q] quitter le script.

    Demandez à l’opérateur de faire un choix parmi les options précédentes.

4. Écrivez la fonction « ``menu`` » qui affiche le menu précédent.

5. Écrire la section des fonctions du script « ``informations-machine`` ».
   - Écrivez la fonction « ``info-systeme`` » qui donne les informations sur le système d’exploitation utilisé. (Utilisez la commande : « ``uname –a`` ».)
   - Écrivez la fonction « ``info-reseau`` » qui affiche les paramètres des interfaces réseaux du système.
   (Utilisez la commande : « ``/sbin/ip a|grep inet|cut –d" " –f6,11`` ».)
   - Écrivez la fonction « ``info-actif`` » qui affiche depuis quand le système fonctionne.
   (Utilisez la commande : « ``uptime`` ».)
   - Écrivez la fonction « ``info-disques`` » qui donne les informations sur l’espace disque.
   (Utilisez la commande : « ``df –h`` ».)
   - Écrivez la fonction « ``info-usagers`` » qui donne les informations sur l’espace disque utilisé par les usagers.
   (Utilisez la commande : « ``du –hs *`` » dans le répertoire ``/home``.)
   - Écrivez la fonction « ``info-html`` » qui écrit l’ensemble de ces informations vers un page html nommée « **informations-machine.html** ».
   (Inspirez vous du code suivant qui utilise la fonction ``info-html``.)
   Ajoutez les autres fonctions.

```
cat << _EOF_ > informations-machine.html
<html>
<head>
<title>$TITRE</title>
</head>
<body>
<h1>$TITRE</h1>
<p>$ENTETE</p>
<h2> informations sur le systeme d’exploitation utilise</h2>
<pre>$(info-systeme)</pre>
</body>
</html>
_EOF_
```

6. Écrire le corps du programme en utilisant les fonctions.
   - Écrivez une boucle
   - Traitement de la boucle : afficher le menu
   - Traitement de la boucle : la lettre « S » lance la fonction ``info-systeme``.
   - Traitement de la boucle : la lettre « R » lance la fonction ``info-reseau``.
   - Traitement de la boucle : la lettre « T » lance la fonction ``info-actif``.
   - Traitement de la boucle : la lettre « D » lance la fonction ``info-disques``.
   - Traitement de la boucle : la lettre « U » lance la fonction ``info-usagers``.
   - Traitement de la boucle : la lettre « H » lance la fonction ``info-html``.
   - Traitement de la boucle : la lettre « q » ou « Q » sort du script.

7. Partir un simple seuveur Http qui publie la page **informations-machine.html**.

