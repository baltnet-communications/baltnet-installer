# About This Project
This repository contains a helper package for setting up [Baltnet Communications](https://www.baltnet.ee) distribution repository. Repository is located at [pkg.baltnet.net](http://pkg.baltnet.net). As this is a non-default distribution point, a custom APT source must be configured and Baltnet signing key must be imported.

Although [pkg.baltnet.net](http://pkg.baltnet.net) contains various setup instructions, this package helps to semi-automate it as much as possible.

# Installation
To install this package, download an appropriate version directly from release page and issue following command:

```
$ sudo dpkg -i baltnet-installer_<version+id>.deb
```
