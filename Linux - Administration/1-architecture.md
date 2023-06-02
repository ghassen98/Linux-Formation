# Architecture de Linux

## Exercice 1 : 

### But : ### 
Savoir identifier le matériel installé et manipuler les modules de la machine.

1. Retrouver les informations suivantes :
   - Quantité de mémoire installée.
   - Le type de processeur ainsi que sa fréquence.
   - Le type de disque et sa capacité.
   - L’interface réseau et son type.

**AIDE** : Utilisez les commandes ``dmesg``, ``lspci``, ou les informations disponibles avec le répertoire « /proc ».

2. Retrouver les informations suivantes :
   - Les interruptions occupées par des périphériques de type PCI.
   - Les interruptions occupées au niveau de toute la machine.
   - Les adresses I/O occupées au niveau de toute la machine.

**AIDE** : Utilisez les commandes ``dmesg``, ``lspci``, ou les informations disponibles avec le répertoire « /proc ».

3. Affichez les modules utilisés et non utilisés de la machine.
4. Supprimez un module figurant dans la liste (non utilisé !)
5. Rechargez le module.

**AIDE** : Utilisez ``lsmod``, ``modprobe`` ainsi que les informations disponibles avec le répertoire « /proc ».

