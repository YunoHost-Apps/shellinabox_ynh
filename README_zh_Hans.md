<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Shell In A Box

[![集成程度](https://dash.yunohost.org/integration/shellinabox.svg)](https://dash.yunohost.org/appci/app/shellinabox) ![工作状态](https://ci-apps.yunohost.org/ci/badges/shellinabox.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/shellinabox.maintain.svg)

[![使用 YunoHost 安装 Shell In A Box](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shellinabox)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Shell In A Box。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Shell In A Box implements a web server that can export arbitrary command line tools to a web based terminal emulator. This emulator is accessible to any JavaScript and CSS enabled web browser and does not require any additional browser plugins.


**分发版本：** 2.21~ynh5

## 截图

![Shell In A Box 的截图](./doc/screenshots/screenshot.gif)

## 文档与资源

- 官方应用网站： <https://code.google.com/archive/p/shellinabox/>
- 官方用户文档： <https://code.google.com/p/shellinabox/wiki/shellinaboxd_man>
- 官方管理文档： <https://github.com/shellinabox/shellinabox/wiki/shellinaboxd_man>
- 上游应用代码库： <https://github.com/shellinabox/shellinabox>
- YunoHost 商店： <https://apps.yunohost.org/app/shellinabox>
- 报告 bug： <https://github.com/YunoHost-Apps/shellinabox_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing --debug
或
sudo yunohost app upgrade shellinabox -u https://github.com/YunoHost-Apps/shellinabox_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
