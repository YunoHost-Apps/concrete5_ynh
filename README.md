# concrete5_ynh

[![Integration level](https://dash.yunohost.org/integration/concrete5.svg)](https://dash.yunohost.org/appci/app/concrete5)  
[![Install concrete5 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=concrete5)

> *This package allow you to install concrete5 quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

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

**Shipped version:** 8.4.5

## Documentation

 * Official documentation: https://documentation.concrete5.org/

## YunoHost specific features

#### Multi-users support

LDAP and HTTP auth are not supported?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/concrete5%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/concrete5/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/concrete5%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/concrete5/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/concrete5%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/concrete5/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/concrete5_ynh/issues
 * App website: https://www.concrete5.org/
 * GitHub App website: https://github.com/concrete5/concrete5
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/concrete5_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/concrete5_ynh/tree/testing --debug
or
sudo yunohost app upgrade concrete5 -u https://github.com/YunoHost-Apps/concrete5_ynh/tree/testing --debug
```
