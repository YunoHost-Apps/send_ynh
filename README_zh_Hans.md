<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Send

[![集成程度](https://dash.yunohost.org/integration/send.svg)](https://dash.yunohost.org/appci/app/send) ![工作状态](https://ci-apps.yunohost.org/ci/badges/send.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/send.maintain.svg)

[![使用 YunoHost 安装 Send](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=send)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Send。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A fork of Mozilla's Firefox Send. Mozilla discontinued Send, this fork is a community effort to keep the project up-to-date and alive.
Send is a file sharing experiment which allows you to send encrypted files to other users.


**分发版本：** 3.4.23~ynh4

**演示：** <https://send.vis.ee/>

## 截图

![Send 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://send.vis.ee/>
- 上游应用代码库： <https://github.com/timvisee/send>
- YunoHost 商店： <https://apps.yunohost.org/app/send>
- 报告 bug： <https://github.com/YunoHost-Apps/send_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/send_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
或
sudo yunohost app upgrade send -u https://github.com/YunoHost-Apps/send_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
