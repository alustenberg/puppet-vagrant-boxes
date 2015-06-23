# puppet-vagrant-boxes

Build fast vagrant-base-boxes for further usage.

forked and updated centos 6.6 target to use ansible rather than puppet

## Requirements

* [virtualbox](https://www.virtualbox.org/)
* [vagrant](https://www.vagrantup.com/)
* [veewee](https://github.com/jedi4ever/veewee)

## Build
```
$ veewee vbox build centos-6.6-x86_64
```

## Export
```
$ veewee vbox export centos-6.6-x86_64
```
