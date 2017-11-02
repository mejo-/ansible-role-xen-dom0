# Ansible role to provision a Xen Dom0

A simple role to install and configure Xen on a Dom0.

# Defaults

```
xen_dom0_dependencies:
  - bridge-utils
  - ifenslave
  - kpartx
  - lvm2
  - xen-tools
  - xen-system-amd64

xen_dom0_divert_grub: yes

xen_dom0_mem: "1024M"

#xen_dom0_lvm_pvs: []
```

# License

This Ansible role is licensed under the GNU GPLv3 or later.

# Author

Copyright 2017 Jonas Meurer <jonas@freesources.org>
