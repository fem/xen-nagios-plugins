# xen-nagios-plugins
Nagios-compatible plugins for collecting statistics for VMs on Xenserver

## Plugins
### Per-VM CPU Statistics
Requires installed python-bindings for libxenstat
```./check_xen_cpu```

### Per-Interface Traffic Statistics
```./check_net```

### LVM Cache Statistics
```./check_lvm_cache /dev/vg0/cached_lv```
