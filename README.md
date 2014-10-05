munin-virtstats
===============

VMの統計を取るmuninプラグイン

Install
-------
```
$ git clone https://github.com/buty4649/munin-virtstats
$ cd munin-virtstats
$ sudo cp munin-virtstats /etc/munin/plugins
$ sudo cp plugin-conf.sample /etc/munin/plugin-conf.d

$ sudo service munin-node restart
```


Require
--------
* libvirt
* cgroups
* Sys::Virt
* XML::Simple
