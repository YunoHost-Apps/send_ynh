# Send pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/send.svg)](https://dash.yunohost.org/appci/app/send) ![](https://ci-apps.yunohost.org/ci/badges/send.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/send.maintain.svg)  
[![Installer Send avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=send)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Send rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Partage de fichier simple et privé

**Version incluse :** 3.4.13~ynh1

**Démo :** https://send.vis.ee/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Configuration

Le chemin du fichier de configuration est `var/www/send/server/config.js`.
Vous pouvez configurer des paramètres tels que les taille de fichier, nombre de téléchargements, ou temps d'expiration des fichiers maximums.

## Documentations et ressources

* Site officiel de l'app : https://send.vis.ee/
* Dépôt de code officiel de l'app : https://github.com/timvisee/send
* Documentation YunoHost pour cette app : https://yunohost.org/app_send
* Signaler un bug : https://github.com/YunoHost-Apps/send_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/send_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
ou
sudo yunohost app upgrade send -u https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps