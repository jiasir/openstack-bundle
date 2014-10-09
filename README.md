openstack-bundle
================

A bundle for deploy an IaaS. You can deploy OpenStack in the MAAS+Juju environment as an easiest way.

### Overview
All of the OpenStack components using lxc isolated. The OpenStack version is IceHouse.

### How to?
* Change the `dataset-size` to modify the database size.
* The `admin-password` is that horizon login password, you can modify the setting.
* `block-device` is the swift storage location or cinder backend location.
* `zone-assignment` is a swift zone assignment.
* Acording to this `network-manager` setting, you can decide what the network driver for your enterprise.
* Attention to the series is trusty.
* Only import the bundle to your juju environment that is worked.