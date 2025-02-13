<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 IFM

[![集成程度](https://apps.yunohost.org/badge/integration/ifm)](https://ci-apps.yunohost.org/ci/apps/ifm/)
![工作状态](https://apps.yunohost.org/badge/state/ifm)
![维护状态](https://apps.yunohost.org/badge/maintained/ifm)

[![使用 YunoHost 安装 IFM](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 IFM。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

The IFM is a web-based filemanager, which comes as a single file solution using HTML5, CSS3, JavaScript and PHP. 

### features

- create/edit files and directories
- copy/move files and directories
- download files and directories
- upload files directly, remotely via URL or per drag & drop
- extract archives (tar, tgz, tar.gz, tar.bz2, zip)
- change permissions
- image preview
- simple authentication (LDAP via `ldap_bind` possible)


**分发版本：** 4.0.2~ynh6

**演示：** <https://ifmdemo.gitea.de/>

## 截图

![IFM 的截图](./doc/screenshots/ifm_screenshot.png)

## 文档与资源

- 上游应用代码库： <https://github.com/misterunknown/ifm>
- YunoHost 商店： <https://apps.yunohost.org/app/ifm>
- 报告 bug： <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
或
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
