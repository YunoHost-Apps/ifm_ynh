<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# IFM para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/ifm.svg)](https://ci-apps.yunohost.org/ci/apps/ifm/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/ifm.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/ifm.maintain.svg)

[![Instalar IFM con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarIFM rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 4.0.2~ynh5

**Demo:** <https://ifmdemo.gitea.de/>

## Capturas

![Captura de IFM](./doc/screenshots/ifm_screenshot.png)

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/misterunknown/ifm>
- Catálogo YunoHost: <https://apps.yunohost.org/app/ifm>
- Reportar un error: <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
o
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
