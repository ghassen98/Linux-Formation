# Gestion des processus

## Exercice 1 : 

### But : ### 
Savoir administrer et gérer les processus d’une machine Linux.

1. Si Firefox est installé, lancer le navigateur internet, retrouver son process id, son parent process id.

**Note** : Vous pouvez tester avec les outils ``xclock-xeyes`` en les installant avec la commande ``apt install x11-apps``.

2. En ligne de commande, lancez la commande ``top``.
Faire un **suspend** du processus.
Retrouvez le **PID** affecté à ce processus puis faites le revenir en avant-plan.

**AIDE** : Utilisez les commandes : ``Ctrl-Z``, ``fg`` et ``top``.

3. En ligne de commande, lancez la commande ``xclock`` en tâche de fond (``&``).
Tuez le processus associé à xclock.

**AIDE** : Utilisez les commandes : ``xclock``, ``kill`` et ``man kill``
