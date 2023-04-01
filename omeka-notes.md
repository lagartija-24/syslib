# Notes for Installing Omeka

**Login Info**

Username: Becky
Password: *same as wordpress*
email: mknoe24@gmail.com

**URLs for for sites**

[Login Screen](http://34.135.201.171/omeka/admin/users/login)
[Admin Dashboard](http://34.135.201.171/omeka/admin)
[My Homepage](http://34.135.201.171/omeka)

## Mysql Database notes from WP

*remember, do not copy pretext*

```
mysql> create user 'omeka'@'localhost' identified by 'password';
```
```
mysql> create database omeka;
```
```
mysql> grant all privileges on omeka.* to 'omeka'@'localhost';
```
```
mysql> show databases;
```
```
mysql> \q
```

## What helped?

1. Rewatching the wordpress video was helpful to remember specific steps
1. Interacting with others in Element who have run across similar issues
1. Breathe and don't overthink
