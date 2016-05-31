### Getting started ###
(Optionally see the [detailed installation instructions](docs/INSTALLING.md) for more information)

#### Supported Linux Distributions ####
For a quick guide to installing Pony Mail, please see the guides for:
- [Debian (Jessie) Installation Instructions](docs/INSTALL.debian.md)
- [Ubuntu (14.04) Installation Instructions](docs/INSTALL.ubuntu.md)
- [CentOS (7.1) Installation Instructions](docs/INSTALL.centos.md)
- [Fedora (22) Installation Instructions](docs/INSTALL.fedora.md)

#### Generic installation instructions ####

1. Install Apache httpd + mod_lua and the lua libs (see http://modlua.org/gs/installing if need be)
2. Install ElasticSearch
3. go to tools/ and run python setup.py - follow the instructions and enter info
4. Fiddle a bit with site/js/config.js for now
5. Add Pony Mail as an archiver for your lists. [see this doc](docs/ARCHIVING.md).
6. import mbox data with import-mbox.py if need be (see [this doc](docs/IMPORTING.md) for details)
7. All done :) But please see the [detailed installation instructions](docs/INSTALLING.md) for more details
