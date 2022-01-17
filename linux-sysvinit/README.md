SysVinit conf for MinIO
=======================

Usage
-----

- [Download MinIO](https://minio.io/downloads) in `/opt/bin/minio`.
- Save the SysVinit config file in `/etc/init.d/minio`.
- Ensure that the folder `/etc/minio` exists.
- Now you can use `service minio start|stop|restart|status` as `root`.
