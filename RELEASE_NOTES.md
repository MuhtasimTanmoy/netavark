# Release Notes

## v1.0.3
* Updated dependenciess
* Simplified option parsing for bridge/macvlan
* Added support for an ipam `none` driver


## v1.0.2
* Fix issue [#13533](https://github.com/containers/podman/issues/13533) - only use systemd when present
* Dropped vergen dependency
* Updated several dependency libraries
* Allow macvlans to not require a default gateway

## v1.0.1

* core,macvlan: add gateway as default route to macvlan interface
* Add host_ip and container_ip version matching to iptables portforwardinhg
* Remove vendor directory from upstream github repo

## v1.0.0
* First official release of netavark

## v1.0.0-RC2
* RC2 containers several bug fixes and code cleanup

## v1.0.0-RC1
* This is the first release candidate of Netavark. All functionality should be working.