Nous allons voir ici comment faire une mise à jour manuellement sur
Jeedom, via la console SSH.

Prérequis 
=========

-   savoir se connecter en SSH à Jeedom

-   connaître les identifiants SSH (voir documentation d'installation)

-   avoir un accès Internet depuis la box Jeedom

> **Wichtig**
>
> Pensez bien à faire et exporter une sauvegarde avant toute mise à jour
> manuelle.

Téléchargement et décompression 
===============================

En SSH, faites :

    sudo su -
    cd /root
    wget https://github.com/jeedom/core/archive/master.zip
    entpacke master.zip
    cp -R core-master/* /var/www/html
    cp -R core-master/.[^.]* /var/www/html

Update 
===========

Toujours en SSH:

    sudo su -
    php /var/www/html/install/update.php mode=force
    chmod 775 -R /var/www/html
    chown www-data:www-data -R /var/www/html

> **Wichtig**
>
> Si votre installation de Jeedom est un peu ancienne, il faut remplacer
> tous les /var/www/html par /usr/share/nginx/www/jeedom
