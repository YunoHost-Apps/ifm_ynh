<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# IFM dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/ifm)](https://ci-apps.yunohost.org/ci/apps/ifm/)
![Status działania](https://apps.yunohost.org/badge/state/ifm)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/ifm)

[![Zainstaluj IFM z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację IFM na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

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


**Dostarczona wersja:** 4.0.2~ynh6

**Demo:** <https://ifmdemo.gitea.de/>

## Zrzuty ekranu

![Zrzut ekranu z IFM](./doc/screenshots/ifm_screenshot.png)

## Dokumentacja i zasoby

- Repozytorium z kodem źródłowym: <https://github.com/misterunknown/ifm>
- Sklep YunoHost: <https://apps.yunohost.org/app/ifm>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
lub
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
