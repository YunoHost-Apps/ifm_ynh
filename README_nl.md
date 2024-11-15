<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# IFM voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/ifm.svg)](https://ci-apps.yunohost.org/ci/apps/ifm/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/ifm.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/ifm.maintain.svg)

[![IFM met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je IFM snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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


**Geleverde versie:** 4.0.2~ynh5

**Demo:** <https://ifmdemo.gitea.de/>

## Schermafdrukken

![Schermafdrukken van IFM](./doc/screenshots/ifm_screenshot.png)

## Documentatie en bronnen

- Upstream app codedepot: <https://github.com/misterunknown/ifm>
- YunoHost-store: <https://apps.yunohost.org/app/ifm>
- Meld een bug: <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
of
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
