<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# IFM pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/ifm.svg)](https://dash.yunohost.org/appci/app/ifm) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/ifm.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/ifm.maintain.svg)

[![Installer IFM avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer IFM rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

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

**Version incluse :** 4.0.2~ynh2

**Démo :** <https://ifmdemo.gitea.de/>

## Captures d’écran

![Capture d’écran de IFM](./doc/screenshots/ifm_screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/misterunknown/ifm>
- YunoHost Store : <https://apps.yunohost.org/app/ifm>
- Signaler un bug : <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
