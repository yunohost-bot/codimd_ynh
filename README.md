<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# CodiMD for YunoHost

[![Integration level](https://dash.yunohost.org/integration/codimd.svg)](https://dash.yunohost.org/appci/app/codimd) ![Working status](https://ci-apps.yunohost.org/ci/badges/codimd.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/codimd.maintain.svg)  
[![Install CodiMD with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=codimd)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install CodiMD quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

CodiMD is the free software version of HackMD, developed and opened source by the HackMD team with reduced features (without book mode), you can use CodiMD for your community and own all your data. [(See the origin of the name CodiMD.)](https://github.com/hackmdio/codimd/issues/720)

CodiMD is perfect for open communities, while HackMD emphasizes on permission and access controls for commercial use cases.

**Shipped version:** 2.4.2~ynh1

## Screenshots

![Screenshot of CodiMD](./doc/screenshots/screenshot.png)

## Disclaimers / important information

### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

### Configuration

You can configure CodiMD by editing this file `/var/www/codimd/config.json` using the [documentation](https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-configuration)

## Documentation and resources

* Official app website: <https://hackmd.io/>
* Official user documentation: <https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-documentation#User-Guides>
* Official admin documentation: <https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-documentation#Administration-Guides>
* Upstream app code repository: <https://github.com/hackmdio/codimd>
* YunoHost documentation for this app: <https://yunohost.org/app_codimd>
* Report a bug: <https://github.com/YunoHost-Apps/codimd_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/codimd_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
or
sudo yunohost app upgrade codimd -u https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
