<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# IFM per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/ifm.svg)](https://dash.yunohost.org/appci/app/ifm) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/ifm.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/ifm.maintain.svg)

[![Installa IFM con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare IFM su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

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


**Versione pubblicata:** 4.0.2~ynh2

**Prova:** <https://ifmdemo.gitea.de/>

## Screenshot

![Screenshot di IFM](./doc/screenshots/ifm_screenshot.png)

## Documentazione e risorse

- Repository upstream del codice dell’app: <https://github.com/misterunknown/ifm>
- Store di YunoHost: <https://apps.yunohost.org/app/ifm>
- Segnala un problema: <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
o
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
