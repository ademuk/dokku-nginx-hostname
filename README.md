dokku-nginx-hostname
========================

Custom app hostnames for dokku (https://github.com/progrium/dokku).

Requirements
------------

Tested on version 0.3.7 of Dokku.

Installation
------------

```bash
$ cd /var/lib/dokku/plugins
$ sudo git clone https://github.com/ademuk/dokku-nginx-hostname.git nginx-hostname
````

Usage
-----

To set hostname
```bash

dokku hostname:set app_name example.com
```
To retrieve hostname
```bash
dokku hostname app_name
```

NOTE: Currently you must re-deploy your app to apply the hostname change.

License
-------

MIT
