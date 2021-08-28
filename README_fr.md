# IFM pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/ifm.svg)](https://dash.yunohost.org/appci/app/ifm) ![](https://ci-apps.yunohost.org/ci/badges/ifm.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/ifm.maintain.svg)  
[![Installer IFM avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer IFM rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

L'IFM est un gestionnaire de fichiers basé sur le Web, qui se présente sous la forme d'un fichier unique utilisant HTML5, CSS3, JavaScript et PHP.

### caractéristiques

- créer/éditer des fichiers et des répertoires
- copier/déplacer des fichiers et des répertoires
- télécharger des fichiers et des répertoires
- télécharger des fichiers directement, à distance via URL ou par glisser-déposer
- extraire les archives (tar, tgz, tar.gz, tar.bz2, zip)
- modifier les autorisations
- aperçu de l'image
- authentification simple (LDAP via `ldap_bind` possible) 

**Version incluse :** 2.6.3~ynh1

**Démo :** https://ifmdemo.gitea.de/

## Captures d'écran

![](./doc/screenshots/ifm_screenshot.png)

## Avertissements / informations importantes

L'IFM est généralement verrouillé dans son propre répertoire (`/home/yunohost.app.ifm`), vous ne pouvez donc pas aller sur d'autres répertoires. Vous pouvez changer cela en définissant `env[IFM_ROOT_DIR] = /home/yunohost.app.ifm` dans la configuration PHP `/etc/php/7.3/fpm/pool.d/ifm.conf` L.434 en vous aidant de cette [documentation](https://github.com/misterunknown/ifm/wiki/Configuration). 
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