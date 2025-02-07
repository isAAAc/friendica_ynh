<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Friendica for YunoHost

[![Integration level](https://dash.yunohost.org/integration/friendica.svg)](https://dash.yunohost.org/appci/app/friendica) ![](https://ci-apps.yunohost.org/ci/badges/friendica.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/friendica.maintain.svg)  
[![Install Friendica with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=friendica)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Friendica quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Friendica is a decentralised communications platform that integrates social communication. The platform links to independent social projects and corporate services.

Friendica connects you effortlessly to a federated communications network of several thousand servers, with more than half a million user registrations. You can directly connect to anyone on Friendica, Mastodon, Diaspora, GnuSocial, Pleroma, or Hubzilla, regardless where each user profile is hosted.

**Shipped version:** 2021.09~ynh1

**Demo:** https://dir.friendica.social/servers

## Screenshots

![](./doc/screenshots/friendica-vier-profile.png)

## Disclaimers / important information

## Installation

### Register a new domain and add it to YunoHost

Before installing, read the [Friendica installation instructions](https://github.com/friendica/friendica/blob/develop/doc/Install.md) for important information about installation.

- Dedicated domain (must install under web root like **https://friendica.example.com/** not **https://example.com/friendica/** )

- Friendica requires browser-approved SSL certificates.

### Install Friendica
Use the YunoHost admin panel to install Friendica by entering the GitHub repo address in the custom app URL:

		https://github.com/YunoHost-Apps/friendica_ynh

### First Login
as explain in the [issue #43](https://github.com/YunoHost-Apps/friendica_ynh/issues/43), 
you need to **create a user** in the login page after the installation:
- **same login** as the 'user admin' login choosed during the installation
- check your mails: you'll have the **password** for this login
- log in with **mail adress** and passport send by mail
- you'll log in with admin rights
- feel free to change your password
 
#### For normal YunoHost users (non-admin):
Normal LDAP users can login through LDAP authentication and create there profiles.

## Documentation and resources

* Official app website: http://friendi.ca
* Official user documentation: https://wiki.friendi.ca/
* Official admin documentation: https://github.com/friendica/friendica/wiki
* Upstream app code repository: https://github.com/friendica/friendica
* YunoHost documentation for this app: https://yunohost.org/app_friendica
* Report a bug: https://github.com/YunoHost-Apps/friendica_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/friendica_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/friendica_ynh/tree/testing --debug
or
sudo yunohost app upgrade friendica -u https://github.com/YunoHost-Apps/friendica_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps
