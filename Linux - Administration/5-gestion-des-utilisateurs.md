# Gestion des utilisateurs et groupes

## Exercice 1 : 

### But : ### 
Savoir gérer les usagers et les groupes d’une machine Linux.

1. Dans le répertoire ``/etc``, identifier et localiser les fichiers de  configuration des usagers du système.
Rechercher les commandes de gestion des utilisateurs.

2. Ajouter un message à l’ouverture du shell qui affiche la date du jour.

3. Créez un groupe nommé « **web** ».

4. Créez un utilisateur « **pierre** ».

5. Créez un utilisateur « **paul** ».

6. Créez un utilisateur « **phil** ».

7. Ajouter le groupe secondaire **web** pour tous les utilisateurs (**pierre**, **paul** et **phil**).

8. Vérifiez les groupes de tous les utilisateurs.

9. Créez un répertoire « **/web/** »

10. Changer le groupe du répertoire **/web** pour le groupe « **web** ».

11. Changez les permissions du répertoire **/web** pour positionner le **SGID**.

12. Configurez un mot de passe pour l'utilisateur **pierre** et activez-le. Faites la même chose avec **paul** et **phil**.

13. Connectez-vous avec l’usager **pierre** et créer un fichier « **test1** » dans le répertoire **/web**.

14. Connectez-vous avec l’usager **paul** et modifier le fichier « **test1** » en ajoutant ou modifiant une ligne.

15. Supprimer l'utilisateur **phil** du groupe **web**.
Connectez-vous avec l’usager **phil** et modifier le fichier « **test1** » en ajoutant ou modifiant une ligne.

16. Avec la commande « ``chage`` », vérifiez la gestion des mots de passe de l’usager « **pierre** ».
    
17. Changez le nombre de jours d’avertissement à 3 jours.

18. Changez la date d’expiration pour le jour de la fin de la formation.
    
19. Désactivez le compte « **phil** » en bloquant le mot de passe.

20. Vérifiez le blocage en essayant de vous connecter avec « **phil** ».

21. Supprimer le mot de passe pour le compte « **phil** ».

22. Vérifiez que la demande du mot de passe n'est plus effective pour l'utilisateur **phil**.
