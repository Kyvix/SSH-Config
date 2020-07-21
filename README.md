# Generate SSH config file

V1.0
19/02/2020

## Script Execution :

1. Execute the script from a local account :

```
sudo ./generate_ssh_config.sh 

```
2. Execute the script from root user (recommended) :

```
./generate_ssh_config.sh

```
## Menu of the script :


         MENU GENERATION SSH
         G --    Générer fichier ssh_config     -------------> Avec cette option vous pourrez créer votre fichier de configuration ssh_config grâce au fichier csv passée en paramètre

         T --    Test de la génération du fichier   -------------> Avec cette option vous pourrez générer un Test vers la sortie standard ( Fortement Recommandé avant de lancer l'option G)

         B --    Backup Réperoire SSH   -------------> Backuper le répertoire /etc/ssh/

         L --    Lister le(s) Backup(s) -------------> Lister tous les backups du répertoire /backup crée par le script si il n'est pas déjà crée

         Q --    QUIT (Quitter le menu) -------------> Quitter le script
Entrez une lettre (parmi les choix possibles) 
puis tapez RETURN

