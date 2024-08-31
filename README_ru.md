<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# IFM для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/ifm.svg)](https://ci-apps.yunohost.org/ci/apps/ifm/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/ifm.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/ifm.maintain.svg)

[![Установите IFM с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ifm)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить IFM быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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


**Поставляемая версия:** 4.0.2~ynh4

**Демо-версия:** <https://ifmdemo.gitea.de/>

## Снимки экрана

![Снимок экрана IFM](./doc/screenshots/ifm_screenshot.png)

## Документация и ресурсы

- Репозиторий кода главной ветки приложения: <https://github.com/misterunknown/ifm>
- Магазин YunoHost: <https://apps.yunohost.org/app/ifm>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/ifm_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/ifm_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
или
sudo yunohost app upgrade ifm -u https://github.com/YunoHost-Apps/ifm_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
