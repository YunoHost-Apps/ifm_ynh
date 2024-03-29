<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# IFM para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/ifm.svg)](https://dash.yunohost.org/appci/app/ifm) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/ifm.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/ifm.maintain.svg)

[![Instalar IFM con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar IFM de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 4.0.2~ynh2

**Demo:** <https://ifmdemo.gitea.de/>

## Capturas de pantalla

![Captura de pantalla de IFM](./doc/screenshots/ifm_screenshot.png)

## Documentación e recursos

- Repositorio de orixe do código: <https://github.com/misterunknown/ifm>
- Tenda YunoHost: <https://apps.yunohost.org/app/ifm>
- Informar dun problema: <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
