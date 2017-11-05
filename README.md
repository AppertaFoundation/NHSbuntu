# nhos-ubuntu-defaults-settings

Default settings and customisations for NHoS created using ubuntu-defaults-template.

## Getting started

### Packaging for launchpad.net
Build and sign source package

`debuild -S`

Push package to launchpad

`dput -f ppa:nhos/ppa nhos-default-settings_0.x.x_source.changes`

### Packaging for packagecloud.io
Build and sign package with key

`dpkg-buildpackage -krobdyke@gmail.com`

Push package to packagecloud

`package_cloud push nhsbuntu/nhos-default-settings/ubuntu/xenial nhos-default-settings_0.x.x_all.deb`
