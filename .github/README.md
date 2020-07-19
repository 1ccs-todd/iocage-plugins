# iocage-plugins
Jailmans iocage plugins for [FreeNAS](http://www.freenas.org), [TrueOS](https://www.trueos.org) and [FreeBSD](http://www.freebsd.org)

Plugin Json files are added to this repo, along with a respective icon in icons/

When a plugin is made it should be added to the INDEX json and
it will appear in iocage's plugin listing if official

# Installing Plugins

## Using Local File
```
iocage fetch -P /the/path/to/jenkins.json ip4_addr="re0|192.168.0.100" -n jenkins
```

## Pulling from Internet
```
iocage fetch --plugins --name "jenkins" ip4_addr="igb0|192.168.0.91"
```
