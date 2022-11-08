# ansible-firehol

Setups FireHOL

## Example playbook

```yaml
---
- hosts: myserver
  user: root
  sudo: False
  roles:
    - role: sunfoxcz.firehol
      wan_interface: eth0 # defaults to eth0
      allow_services:
        - ping
        - ssh
        - http
        - https
        - ftp
```

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
