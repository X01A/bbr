## indexyz.bbr
Install new kernel and enable TCP BBR congestion control

## Example Playbook
```yaml
- hosts: servers
  roles:
    - role: indexyz.bbr
      start_nginx: yes
```

### Support System
- CentOS 7

### License
MIT
