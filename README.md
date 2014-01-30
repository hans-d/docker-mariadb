MariaDB docker environment
==========================

On first start, it will boostrap the environment. At that time also the 
root password must be provided via `-e MARIADB_ROOT_PASSWD=secret`.

Versions/Branches
-----------------
Due to current limitations of trusted builds these are seperate docker repos.

- `master` -> hansd/mariadb
  - Maria DB standalone

Volumes
-------
- `/var/lib/mqsql`: database, logging
- `/etc/mysql/conf.d`: additional configuration

Ports
-----
- `3306`: mysql / mariadb port

TODO
----
- more secure password setting on boot
