imdock-ftp-server
====================================================

easy use ftp server by [https://github.com/stilliard/docker-pure-ftpd](docker-pure-ftpd)

## Getting Started
```bash
$ git clone https://github.com/imagine10255/imdock-ftp-server.git ftp-server
$ cd ftp-server

# remove git version control
$ rm -rf ./.git

# Modify Config
ftp user account -> FTP_USER_NAME, FTP_USER_HOME, volumes/data
ftp user password -> FTP_USER_PASS
ftp user uid, pid -> FTP_USER_UID, FTP_USER_GID (same your os login account)


# Starting
$ docker-compose up

# Remove
$ docker-compose down -v

```
