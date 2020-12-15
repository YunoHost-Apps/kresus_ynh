# Kresus for YunoHost

[![Integration level](https://dash.yunohost.org/integration/kresus.svg)](https://dash.yunohost.org/appci/app/kresus) ![](https://ci-apps.yunohost.org/ci/badges/kresus.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/kresus.maintain.svg)   
[![Install Kresus with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=kresus)

> *This package allows you to install Kresus quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

Kresus is an open-source libre self-hosted personal finance manager. It allows you to safely track your banking history, check your overall balance and know exactly how you are spending money using categories!

**Shipped version:** 0.16.0

## Screenshots

![Kresus reports view](https://kresus.org/images/pages/view-all-accounts.png?20200420)

## Demo

* [Official demo](https://kresus.org/en/demo.html) ⚠️ Don't set up a connection to your bank accounts, or everybody would be able to look at your private bank information!

## Configuration

## Documentation

* Official documentation: https://kresus.org/en/doc.html

## YunoHost specific features

### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/kresus%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/kresus/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/kresus%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/kresus/)

32 bits architectures are not supported because nodejs does not provide builds for 32 bits anymore.

## Limitations

* By default, all users have access to the accounts. Need to manually select authorised user through YunoHost Administration Panel.

# Additional information

## Roadmap

* works fine:

  * [x] install/remove/backup/remove/upgrade with x86_64

* to be confirmed
  * [x] ARM support

* to be added:
  * [ ] Email support
  * [ ] Improve log file and add logrotate
  * [ ] Add user who will access the app (by default every one has access to the installed app)

## Links

 * Report a bug about this package: https://github.com/YunoHost-Apps/kresus_ynh
 * Report a bug about Kresus itself: https://framagit.org/kresusapp/kresus
 * Kresus website: https://kresus.org
 * YunoHost website: https://yunohost.org
 
---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/kresus_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/kresus_ynh/tree/testing --debug
or
sudo yunohost app upgrade kresus -u https://github.com/YunoHost-Apps/kresus_ynh/tree/testing --debug
```
