# Ansible - Raspberry Pi

### Usage

1. Add **`users.yml`**

```yml
# example
users: 
  - name: username
    password: password
    group: group
```

2. Run
```bash
ansible-playbook pb-raspi.yml --ask-pass # default is "raspberry"
```

### License
MIT
