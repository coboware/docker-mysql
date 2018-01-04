### Description
Added extra functionality on top off the mysql image
* dump
> docker exec [ container-id ] dump

* restore
 >docker exec [ container-id ] restore [archive directory]

* list
 >docker exec [ container-id ] list

Example usage:
```
  $ docker run -d -p 3306:3306 -v ~/share:/share  coboware/docker-mysql
```
### Volumes
Mountpoint **/share** enable u to dump and restore files and create archives for backup outside the container

### Envirionment
MYSQL_EMPTY_PASSWORD yes


[![coboware](https://avatars0.githubusercontent.com/u/30603725?v=4&s=80)](https://github.com/coboware/docker-mysql)
