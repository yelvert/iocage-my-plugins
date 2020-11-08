# iocage-my-plugins
Plugin manifest files for [iocage](https://github.com/iocage/iocage).  These files provide a convenient way to create a jail, preconfigured with some software.

## Prerequisites
A \*BSD system with the [iocage](https://github.com/iocage/iocage) jailmanager.

## Installing Plugins
Download a plugin manifest file to your local file system.
```
fetch https://raw.githubusercontent.com/yelvert/iocage-my-plugins/master/bitwardenrs.json
```
Install the plugin.  Adjust the network settings as needed.
```
iocage fetch -P bitwardenrs.json -n BitwardenRS
```

## Plugin manifest files
### bitwardenrs.json
This will install [BitwardenRS](https://github.com/dani-garcia/bitwarden_rs).
