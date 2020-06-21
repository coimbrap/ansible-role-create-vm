# Ansible Role - Create VM

Role Ansible pour créer des VM KVM sous Proxmox.

### playbooks/vars/pve_credentials.yml
```yaml
user_pve: root@pam
passwd_pve: strongpass
host_pve: pve.elukerio.org
```

### host_vars/vm/vm.yml
```yaml
vm_name: OPNsense
node_bastion: minos
vm_ip: 10.0.0.2
vm_size: 10
vm_iso: OPNsense-20.1-OpenSSL-dvd-amd64.iso
vm_core: 1
vm_os: other
vm_onboot: 1
vm_id: 143
node: jupiter
pve_vol: local-zfs
bridge_main: vmbr0
bridge_second: vmbr1
```
