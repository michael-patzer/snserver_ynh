<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Standard Notes Server for YunoHost

[![Integration level](https://dash.yunohost.org/integration/snserver.svg)](https://dash.yunohost.org/appci/app/snserver) ![](https://ci-apps.yunohost.org/ci/badges/snserver.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/snserver.maintain.svg)  
[![Install Standard Notes Server with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=snserver)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Standard Notes Server quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

The Standard Notes syncing server. An end-to-end encrypted note-taking app.

**Shipped version:** 2022.02.21~ynh1

**Demo:** https://standardnotes.org/demo

## Disclaimers / important information

* No single-sign on or LDAP integration
* Ram requirements (Swap memory will be created during install):
    * The app requires at least 800MB of RAM to work properly.
    * The app requires at least 1000MB of RAM to start.
    * The app requires at least 1500MB of RAM to install.

* The ".env" config-files are stored under "/opt/yunohost/$app/live/"
* You can change the url of this app, but than all useres have to reinstall the extensions.

## Documentation and resources

* Official app website: https://standardnotes.org/
* Official user documentation: https://standardnotes.com/help
* Official admin documentation: https://docs.standardnotes.org/
* Upstream app code repository: https://github.com/standardnotes/standalone
* YunoHost documentation for this app: https://yunohost.org/app_snserver
* Report a bug: https://github.com/YunoHost-Apps/snserver_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/snserver_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/snserver_ynh/tree/testing --debug
or
sudo yunohost app upgrade snserver -u https://github.com/YunoHost-Apps/snserver_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps