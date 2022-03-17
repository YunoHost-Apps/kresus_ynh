# Kresus pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/kresus.svg)](https://dash.yunohost.org/appci/app/kresus) ![](https://ci-apps.yunohost.org/ci/badges/kresus.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/kresus.maintain.svg)
[![Installer Kresus avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kresus)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Kresus rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Kresus is an open-source libre self-hosted personal finance manager. It allows you to safely track your banking history, check your overall balance and know exactly how you are spending money using categories!


**Version incluse :** 0.17.4~ynh2



## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Demo

* [Official demo](https://kresus.org/en/demo.html) Don't set up a connection to your bank accounts, or everybody would be able to look at your private bank information!

32 bits architectures are not supported because nodejs does not provide builds for 32 bits anymore.

## Limitations

* By default, all users have access to the accounts. The admin needs to manually select the authorised user through YunoHost Administration Panel.

## Roadmap

* works fine:

  * [x] install/remove/backup/remove/upgrade with x86_64

* to be confirmed
  * [x] ARM support

* to be added:
  * [ ] URL cannot be changed
  * [ ] Email support
  * [ ] Improve log file and add logrotate
  * [ ] Add user who will access the app (by default every one has access to the installed app)

## Documentations et ressources

* Site officiel de l'app : https://framagit.org/kresusapp/kresus
* Documentation officielle de l'admin : https://kresus.org/en/doc.html
* Dépôt de code officiel de l'app : https://framagit.org/kresusapp/kresus
* Documentation YunoHost pour cette app : https://yunohost.org/app_kresus
* Signaler un bug : https://github.com/YunoHost-Apps/kresus_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/kresus_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/kresus_ynh/tree/testing --debug
ou
sudo yunohost app upgrade kresus -u https://github.com/YunoHost-Apps/kresus_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps