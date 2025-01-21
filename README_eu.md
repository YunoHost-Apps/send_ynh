<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Send YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/send)](https://ci-apps.yunohost.org/ci/apps/send/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/send)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/send)

[![Instalatu Send YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=send)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Send YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A fork of Mozilla's Firefox Send. Mozilla discontinued Send, this fork is a community effort to keep the project up-to-date and alive.
Send is a file sharing experiment which allows you to send encrypted files to other users.


**Paketatutako bertsioa:** 3.4.23~ynh6

**Demoa:** <https://send.vis.ee/>

## Pantaila-argazkiak

![Send(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://send.vis.ee/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/timvisee/send>
- YunoHost Denda: <https://apps.yunohost.org/app/send>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/send_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/send_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
edo
sudo yunohost app upgrade send -u https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
