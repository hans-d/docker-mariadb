MariaDB docker environment
==========================

Versions/Branches
-----------------
Due to current limitations of trusted builds these are seperate docker repos.

- `master` -> hansd/mariadb
  - Maria DB standalone
  - On first start, it will boostrap the environment. At that time also the 
    root password must be provided via `-e MARIADB_ROOT_PASSWD=secret`.
- `client` -> hansd/mariadb-client


Volumes
-------
- `/var/lib/mqsql`: database, logging
- `/etc/mysql/conf.d`: additional configuration

Ports
-----
n/a

