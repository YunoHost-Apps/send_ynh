# Send pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/send.svg)](https://dash.yunohost.org/appci/app/send) ![](https://ci-apps.yunohost.org/ci/badges/send.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/send.maintain.svg)  
[![Installer HedgeDoc avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=send)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer HedgeDoc rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
HedgeDoc est un service web de traitement de texte collaboratif en temps réel. Il utilise le langage Markdown.

**Version incluse :** 3.0.22

## Captures d'écran

![]()

## Démo

* [Démo officielle]()

## Configuration

Vous pouvez configurer HedgeDoc en modifiant le fichier `/var/www/hedgedoc/config.json` et en vous aidant de la [documentation](https://github.com/hedgedoc/server/blob/master/docs/configuration.md)

## Documentation

 * Documentation officielle : https://github.com/kiwiirc/kiwiirc/wiki
 * Documentation YunoHost : 

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/send%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/send/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/send%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/send/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/kiwiirc_ynh/issues
 * Dépôt de l'application principale : https://github.com/mozilla/send
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/send_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
ou
sudo yunohost app upgrade send -u https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
```
