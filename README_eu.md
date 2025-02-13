<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# IFM YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/ifm)](https://ci-apps.yunohost.org/ci/apps/ifm/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/ifm)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/ifm)

[![Instalatu IFM YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek IFM YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 4.0.2~ynh6

**Demoa:** <https://ifmdemo.gitea.de/>

## Pantaila-argazkiak

![IFM(r)en pantaila-argazkia](./doc/screenshots/ifm_screenshot.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/misterunknown/ifm>
- YunoHost Denda: <https://apps.yunohost.org/app/ifm>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
edo
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
