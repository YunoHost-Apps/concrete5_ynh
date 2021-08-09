# Concrete5 pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/concrete5.svg)](https://dash.yunohost.org/appci/app/concrete5) ![](https://ci-apps.yunohost.org/ci/badges/concrete5.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/concrete5.maintain.svg)  
[![Installer Concrete5 avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=concrete5)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Concrete5 rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Système de gestion de contenu Open Source pour les équipes

**Version incluse :** 8.5.5~ynh1



## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * LDAP and HTTP auth are not supported

## Documentations et ressources

* Site officiel de l'app : https://www.concrete5.org/
* Documentation officielle de l'admin : https://documentation.concrete5.org/
* Dépôt de code officiel de l'app : https://github.com/concrete5/concrete5
* Documentation YunoHost pour cette app : https://yunohost.org/app_concrete5
* Signaler un bug : https://github.com/YunoHost-Apps/concrete5_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/concrete5_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/concrete5_ynh/tree/testing --debug
ou
sudo yunohost app upgrade concrete5 -u https://github.com/YunoHost-Apps/concrete5_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps