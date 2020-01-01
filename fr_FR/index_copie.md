# Description

Outil de sauvegarde et de synchronisation de fichiers depuis votre installation Jeedom et plusieurs services de cloud publics. ATTENTION : le plugin ne supporte actuellement que FTP, SFTP, Local, Dropbox, Google Drive et NextCloud",

# Configuration

Le plugin ne comporte pas de configuration générale, il faut ajouter :

> - Equipement "Température"
> - Equipement "Humidité Relative"

> en option
> - Equipement "Pression Atmosphérique" : Pression atmosphérique réelle sur le site. 1013.25 hPa par défaut si non renseignée
> - Seuil (°C) : Seuil de déclenchement de l'alerte rosée, 2°C par défaut (dépression du point de rosée T°-Tr°) A ajuster en fonction des observations locales.
-- 
Il faut ajouter un équipement pour la température et un équipement pour l’humidité

# Ajouter un équipement 
- Cliquer sur "Ajouter"
- Donner un nom à l'équipement (Exemple : Sauvegarde Jeedom)
- Cliquer sur OK

# Paramétrer une sauvegarde FTP
Dans l'onglet "Configuration" 
![FTP](../images/FTP.png)
- Sélectionner Type de stockage : FTP
- Indiquer l’adresse FTP de votre serveur, il peut être local mais aussi externe.
- Indiquer le Port FTP (par défaut 21)
- Indiquer le nom d'utilisateur du serveur FTP
- Indiquer le mot de passe du serveur FTP

# Paramétrer une sauvegarde SFTP
Dans l'onglet "Configuration" 
![SFTP](../images/SFTP.png)
- Sélectionner Type de stockage : SFTP
- Indiquer l’adresse SFTP de votre serveur, il peut être local mais aussi externe.
- Indiquer le Port SFTP (par défaut 22)
- Indiquer le nom d'utilisateur du serveur SFTP
- Indiquer le mot de passe du serveur SFTP

# Paramétrer une sauvegarde Dropbox
## Création d'un compte 
- Si vous n’avez pas de compte dropbox suivez le lien suivant pour en créer un.
<a href="https://db.tt/2rbL2XvvHz">https://db.tt/2rbL2XvvHz</a>

## Récupération du Token
- Pour commencer il va falloir créer une application dropbox afin de récupérer un token indispensable au plugin cloudsync  pro pour fonctionner

- Allez à l’adresse suivante <a href="https://www.dropbox.com/developers/apps">https://www.dropbox.com/developers/apps</a>
- Cliquer sur "Create app"
![Dropbox 1](../images/DROPBOX_1.png)
- Donner un nom à votre application (exemple VotrePseudo_JEEDOM_SAUV)
- Cocher "I agree …"
- Cliquer sur  "Create App"
- Générer le token pour permettre à cloudsync pro de contacter votre application
- Copier le token
![Dropbox 2](../images/DROPBOX_2.png)

## Configuration
Dans l'onglet "Configuration" 
![DROPBOX](../images/SFTP.png)
- Sélectionner Type de stockage : DROPBOX
- Indiquer le token : Coller le token précédemment copier

# Paramétrer une sauvegarde Google Drive

# Paramétrer uune sauvegarde NestCloud

# Paramétrer uune sauvegarde Local

# Ajouter les commandes sur l'équipement
Dans l'onglet "Commandes" 
## Ajouter une commande de Sauvegarde
- Cliquer sur "Ajouter une commande"
- Donner un nom à la commande (Exemple : Backup)
![Commandes_1](../images/Commandes_1.png)
- Dans la partie configuration
    - Sélectionner "Copie (Source vers destination)
    - Indiquer la source : Dossier de sauvegarde local de Jeedom (Par défaut /var/www/html/backup)
    - Indiquer la destination : Dossier de destination
- Dans la partie Paramètres
    - Indiquer l'inclusion  des fichiers : mettre "*.gz"
    