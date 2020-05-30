# concrete5_ynh

[![Integration level](https://dash.yunohost.org/integration/concrete5.svg)](https://dash.yunohost.org/appci/app/concrete5) ![](https://ci-apps.yunohost.org/ci/badges/concrete5.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/concrete5.maintain.svg)  
[![Install concrete5 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=concrete5)

> *This package allows you to install concrete5 quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Concrete5 is a modern CMS.
Features : 
* SEO Tools
* User mangament
* Secure
* Intuitive Editing
* Theme and Block management
* Marketing tools
* **and more**...

**Shipped version:** 8.5.2

## Documentation

 * Official documentation: https://documentation.concrete5.org/

## YunoHost specific features

#### Multi-users support

LDAP and HTTP auth are not supported

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/concrete5%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/concrete5/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/concrete5%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/concrete5/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/concrete5_ynh/issues
 * App website: https://www.concrete5.org/
 * GitHub App website: https://github.com/concrete5/concrete5
 * YunoHost website: https://yunohost.org/

---

Developer info
----------------

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/concrete5_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/concrete5_ynh/tree/testing --debug
or
sudo yunohost app upgrade concrete5 -u https://github.com/YunoHost-Apps/concrete5_ynh/tree/testing --debug
```
