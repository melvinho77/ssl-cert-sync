# ansible-role-freeipa-sync

Install and configure freeipa client.

## Requirements

- `ansible-ssl-cert-sync`

## Role Variables

**None**

## Example Playbook

```
- hosts: all
  become: true
  roles:
    - role: ansible-ssl-cert-sync
```
