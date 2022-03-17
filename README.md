<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Kresus for YunoHost

[![Integration level](https://dash.yunohost.org/integration/kresus.svg)](https://dash.yunohost.org/appci/app/kresus) ![](https://ci-apps.yunohost.org/ci/badges/kresus.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/kresus.maintain.svg)  
[![Install Kresus with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kresus)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Kresus quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Kresus is an open-source libre self-hosted personal finance manager. It allows you to safely track your banking history, check your overall balance and know exactly how you are spending money using categories!


**Shipped version:** 0.17.4~ynh2



## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

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

## Documentation and resources

* Official app website: https://framagit.org/kresusapp/kresus
* Official admin documentation: https://kresus.org/en/doc.html
* Upstream app code repository: https://framagit.org/kresusapp/kresus
* YunoHost documentation for this app: https://yunohost.org/app_kresus
* Report a bug: https://github.com/YunoHost-Apps/kresus_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/kresus_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/kresus_ynh/tree/testing --debug
or
sudo yunohost app upgrade kresus -u https://github.com/YunoHost-Apps/kresus_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps