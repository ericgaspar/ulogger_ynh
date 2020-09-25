# μlogger for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ulogger.svg)](https://dash.yunohost.org/appci/app/ulogger) ![](https://ci-apps.yunohost.org/ci/badges/ulogger.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/ulogger.maintain.svg)  
[![Install μlogger with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=ulogger)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install μlogger quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

This is a web application for real-time collection of geolocation data, tracks viewing and management. Together with a dedicated [μlogger mobile client](https://github.com/bfabiszewski/ulogger-android) it may be used as a complete self hosted server–client solution for logging and monitoring users' geolocation.

**Version:** 1.0

- [μlogger](https://github.com/bfabiszewski/ulogger-server)

## Live demo:
- http://ulogger.fabiszewski.net/ (test track upload and editing, login: demo, password: demo)

## Features:
- simple
- allows live tracking
- track statistics
- altitudes graph
- multiple users
- user authentication
- Google Maps API v3
- OpenLayers v2 or v3 (OpenStreet and other layers)
- ajax
- user preferences stored in cookies
- simple admin menu
- export tracks to gpx and kml
- import tracks from gpx

## To-Do's
- [ ] Use config file from the sources rather then conf/config.php for the configuration.

**Multi-user:** Yes

## Screenshots

![](Link to a screenshot of this app.)

## Demo

* [Official demo](http://ulogger.fabiszewski.net/)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/REPLACEBYYOURAPP/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/REPLACEBYYOURAPP%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/REPLACEBYYOURAPP/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/issues
 * App website: Link to the official website of this app.
 * Upstream app repository: Link to the official repository of the upstream app.
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing --debug
or
sudo yunohost app upgrade REPLACEBYYOURAPP -u https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing --debug
```
