
wsl --installl
    wsl --install :
    Cette commande est utilisée pour installer Windows Subsystem for Linux (WSL) sur une machine Windows. Elle permet de configurer et d’installer un environnement Linux directement sur Windows, sans avoir besoin d’une machine virtuelle. Par exemple, vous pouvez installer des distributions comme Ubuntu, Debian, etc.

    Sudoers :
    Il s’agit du fichier /etc/sudoers, qui définit les permissions pour les utilisateurs afin d’exécuter des commandes avec des privilèges superutilisateur (root). Ce fichier est crucial pour la sécurité du système. Pour le modifier, on utilise la commande visudo, qui ouvre le fichier en mode sécurisé pour éviter les erreurs de syntaxe.

    mettre à jour:
    La commande sudo apt update (sur les systèmes basés sur Debian/Ubuntu) est utilisée pour mettre à jour la liste des paquets disponibles dans les dépôts. Elle ne met pas à jour les logiciels eux-mêmes, mais elle synchronise les informations sur les versions disponibles.

    NetPlan :
    Netplan est un outil de configuration réseau utilisé dans les distributions Linux modernes (comme Ubuntu). Il permet de configurer les interfaces réseau via des fichiers YAML situés dans /etc/netplan/. Après avoir modifié un fichier Netplan, on applique les changements avec la commande sudo netplan apply.

    nano :
    Nano est un éditeur de texte en ligne de commande, simple et convivial. Il est souvent utilisé pour modifier des fichiers de configuration. Par exemple, pour éditer un fichier, on utilise :
    cogner
    Copier

    nano nom_du_fichier

    Système CTL :
    systemctl est un outil de gestion des services et des démons (daemons) sur les systèmes Linux utilisant systemd (comme Ubuntu, Debian, CentOS, etc.). Il permet de démarrer, arrêter, redémarrer ou vérifier l’état des services. Par exemple :

        Démarrer un service : sudo systemctl start nom_du_service

     Vérifier l’état d’un service : sudo systemctl status nom_du_service

    Lien IP Afficher :
    Cette commande affiche les informations sur les interfaces réseau disponibles sur votre système, comme les cartes Ethernet ou Wi-Fi. Elle montre l’état des interfaces (actives ou inactives) et leurs adresses MAC.

    IP A (ou IP addr) :
    Cette commande affiche les adresses IP attribuées aux interfaces réseau, ainsi que d’autres informations comme les adresses IPv4, IPv6, et l’état des interfaces.

    CD:
    La commande cd (Change Directory) est utilisée pour naviguer entre les répertoires du système de fichiers. Par exemple :

        Aller dans le répertoire home : cd ~

     Remonter d’un niveau : cd ..

    Ps:
    La commande ps affiche les processus en cours d’exécution sur le système. Par exemple : 123

        Voir tous les processus : ps aux

        Filtrer par utilisateur : ps -u nom_utilisateur

    démon:
    Un daemon (ou démon) est un programme qui s’exécute en arrière-plan, sans interaction directe avec l’utilisateur. Les démons sont souvent utilisés pour des services système, comme un serveur web ou un service de gestion de fichiers. Par exemple, sshd est le daemon pour le service SSH.
