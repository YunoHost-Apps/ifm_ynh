# IFM pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/ifm.svg)](https://dash.yunohost.org/appci/app/ifm) ![](https://ci-apps.yunohost.org/ci/badges/ifm.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/ifm.maintain.svg)  
[![Installer IFM avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer IFM rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

### features

- create/edit files and directories
- copy/move files and directories
- download files and directories
- upload files directly, remotely via URL or per drag & drop
- extract archives (tar, tgz, tar.gz, tar.bz2, zip)
- change permissions
- image preview
- simple authentication (LDAP via ldap_bind possible)


**Version incluse :** 2.6.3~ynh1

**Démo :** https://ifmdemo.gitea.de/

## Captures d'écran

![](./doc/screenshots/ifm_screenshot.png)

## Avertissements / informations importantes

The IFM is usually locked to it's own directory, so you are not able to go above. You can change that by setting the root_dir in the scripts [configuration](https://github.com/misterunknown/ifm/wiki/Configuration).
## Documentations et ressources

* Site officiel de l'app : https://github.com/misterunknown/ifm
* Dépôt de code officiel de l'app : https://github.com/misterunknown/ifm
* Documentation YunoHost pour cette app : https://yunohost.org/app_ifm
* Signaler un bug : https://github.com/YunoHost-Apps/ifm_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps