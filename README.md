<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Send for YunoHost

[![Integration level](https://dash.yunohost.org/integration/send.svg)](https://dash.yunohost.org/appci/app/send) ![Working status](https://ci-apps.yunohost.org/ci/badges/send.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/send.maintain.svg)  
[![Install Send with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=send)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Send quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A fork of Mozilla's Firefox Send. Mozilla discontinued Send, this fork is a community effort to keep the project up-to-date and alive.
Send is a file sharing experiment which allows you to send encrypted files to other users.


**Shipped version:** 3.4.21~ynh1

**Demo:** https://send.vis.ee/

## Screenshots

![Screenshot of Send](./doc/screenshots/screenshot.png)

## Disclaimers / important information

## Configuration

The config file path is `var/www/send/server/config.js`.
You can configure things such as the max file size, max downloads, or max file expire time.

## Documentation and resources

* Official app website: <https://send.vis.ee/>
* Upstream app code repository: <https://github.com/timvisee/send>
* YunoHost documentation for this app: <https://yunohost.org/app_send>
* Report a bug: <https://github.com/YunoHost-Apps/send_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/send_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
or
sudo yunohost app upgrade send -u https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
