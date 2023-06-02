# Gestion des tâches

## Exercice 1 : 

### But : ### 
Savoir programmer des tâches.

1. En ligne de commande, planifiez l’affichage de la date dans une minute.

**AIDE** : Utilisez les commandes : ``at`` et ``mail``.

2. Avec ``cron``, planifiez l’affichage de la date que vous redirigerez dans un fichier à toutes les minutes.

**AIDE** : Utilisez les commandes : ``crontab`` et ``man 5 crontab``.

**NOTE** : Pour permettre à un utilisateur non-root d'utiliser les outils cron, il faut lui ajouter au fichier ``/etc/cron.allow``

```
touch /etc/cron.allow
echo "techno" > /etc/cron.allow
```
