<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# IFM untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/ifm.svg)](https://ci-apps.yunohost.org/ci/apps/ifm/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/ifm.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/ifm.maintain.svg)

[![Pasang IFM dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang IFM secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 4.0.2~ynh5

**Demo:** <https://ifmdemo.gitea.de/>

## Tangkapan Layar

![Tangkapan Layar pada IFM](./doc/screenshots/ifm_screenshot.png)

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://github.com/misterunknown/ifm>
- Gudang YunoHost: <https://apps.yunohost.org/app/ifm>
- Laporkan bug: <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
atau
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
