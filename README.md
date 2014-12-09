dokku-nginx-hostname
========================

Cstom app hostnames for dokku (https://github.com/progrium/dokku).

Requirements
------------

Tested on vesrion 0.3.7 of Dokku.

Installation
------------

```bash
$ cd /var/lib/dokku/plugins
$ sudo git clone https://github.com/ademuk/dokku-nginx-hostname.git nginx-hostname
````

Usage
-----

In your applications folder (/home/dokku/app_name) create a file called HOSTNAME.

Inside this file list one or more hostnames. For example:

```bash
example.com
```
or
```bash
example.com example.net
```

License
-------

MIT
