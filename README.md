Debian 8 (Jessie) Sensu core image
==================================

[![Build Status](https://travis-ci.org/jebovic/docker-debianjessie-sensu-core.svg?branch=master)](https://travis-ci.org/jebovic/docker-debianjessie-sensu-core) [![Docker hub](https://img.shields.io/badge/hub.docker.com-jebovic/debianjessie--sensu--core-blue.svg?style=flat)](https://hub.docker.com/r/jebovic/debianjessie-sensu-core)

How to Use
----------

```
docker run -d -i -p 3030:3030 -p 4567:4567 --name sensu-core jebovic/debianjessie-sensu-core
```

Notes
-----

You can customize Sencu Server and Sensu API configuration in /etc/sensu/conf.d

License
-------

MIT

Author Information
------------------

Jérémy Baumgarth https://github.com/jebovic
