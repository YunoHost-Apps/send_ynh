<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Send pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/send)](https://ci-apps.yunohost.org/ci/apps/send/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/send)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/send)

[![Installer Send avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=send)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Send rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Un fork du Firefox Send de Mozilla. Mozilla a arrêté Send, et ce fork est un effort de la communauté pour maintenir le projet en vie.
Send est une expérience de partage de fichiers qui permet d'envoyer des fichiers chiffrés à d'autres utilisateurs.


**Version incluse :** 3.4.23~ynh6

**Démo :** <https://send.vis.ee/>

## Captures d’écran

![Capture d’écran de Send](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://send.vis.ee/>
- Dépôt de code officiel de l’app : <https://github.com/timvisee/send>
- YunoHost Store : <https://apps.yunohost.org/app/send>
- Signaler un bug : <https://github.com/YunoHost-Apps/send_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/send_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
ou
sudo yunohost app upgrade send -u https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
