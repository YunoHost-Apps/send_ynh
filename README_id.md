<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Send untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/send.svg)](https://ci-apps.yunohost.org/ci/apps/send/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/send.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/send.maintain.svg)

[![Pasang Send dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=send)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Send secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A fork of Mozilla's Firefox Send. Mozilla discontinued Send, this fork is a community effort to keep the project up-to-date and alive.
Send is a file sharing experiment which allows you to send encrypted files to other users.


**Versi terkirim:** 3.4.23~ynh5

**Demo:** <https://send.vis.ee/>

## Tangkapan Layar

![Tangkapan Layar pada Send](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://send.vis.ee/>
- Depot kode aplikasi hulu: <https://github.com/timvisee/send>
- Gudang YunoHost: <https://apps.yunohost.org/app/send>
- Laporkan bug: <https://github.com/YunoHost-Apps/send_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/send_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
atau
sudo yunohost app upgrade send -u https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
