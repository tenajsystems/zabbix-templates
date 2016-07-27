# Template for lvm thin pool

Template makes autodiscovery **thin pool** volumes and monitor **Data** and **Metadata** size for them

## Requires
sudo for user **zabbix**
```
zabbix ALL = (root) NOPASSWD: /sbin/lvs
```

## Tested for
- Ubuntu 16.04
