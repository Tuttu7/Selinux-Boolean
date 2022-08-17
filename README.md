#### Booleans allow parts of SELinux policy to be changed at runtime, without any knowledge of SELinux policy writing. The getsebool -a command lists Booleans, whether they are on or off, but does not give a description of each one.

```
getsebool -a | grep -i ftp_home_dir
```

#### To change boolean value from off to on  ( permanently ):

```
setsebool -P ftphome_dir on
```
#### Selinux log files :

/var/log/messsages

/var/log/audit



