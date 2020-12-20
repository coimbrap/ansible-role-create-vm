# Ansible Role - Create VM

Role Ansible pour créer des VM KVM sous Proxmox.

### Example

#### Credentials

```yaml
user_pve: root@pam
passwd_pve: strongpass
host_pve: pve.exemple.com
```

#### Vars

```yaml
vm_name: OPNsense
vm_ip: 10.0.10.254
vm_size: 10
vm_iso: OPNsense-20.7-OpenSSL-dvd-amd64.iso
vm_core: 1
vm_os: other
vm_onboot: 1
vm_id: 254
node: pve
pve_vol: local-zfs
bridge_main: vmbr1
node_bastion: bastion1
```

### License

GPLv3

### Author Information

Pierre Coimbra
