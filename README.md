# Start MySQL
---
## Install mysql in MacOS
- Install homebrew
```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew update
```
- Install mysql
```
$ brew search mysql
$ brew install mysql
```
## Login in mysql
```
$ mysql -u root -p
```
## Setting password in mysql
```
$ mysql_secure_installation
```
## Exit mysql
```
mysql> exit
```
