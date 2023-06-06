# Gestion des applications - Webmin

## Exercice 1 : 

### But : ### 
Savoir manipuler le gestionnaire de paquages APT et installer Webmin.

1. Mettez à jour le fichier de liste de packages ``/etc/apt/sources.list``.

2. Téléchargez et installez les mises à jour des packages.

3. Installez des packages de dépendance ``software-properties-common`` pour vous aider à gérer les dépôts de logiciels ainsi que le package de support d'accès aux dépôts via Https ``apt-transport-https``.

4. Ajoutez la clé GPG de Webmin au gestionnaire **Apt**.

5. Ajoutez le lien vers le dépôt de Webmin au gestionnaire **Apt**.

6. Installez Webmin.

7. Vérifiez le statut du service Webmin.

8. Si vous avez un parefeu actif, ajoutez une règle pour autoriser l'accès au port 10000/tcp utilisé par Webmin.

9. Changez le mot de passe root de Webmin en utilisant le script ``/usr/share/webmin/changepass.pl``.

10. Accédez au tableau de bord Webmin en utilisant votre navigateur web via ``https://[your server's IP]:10000/``.

