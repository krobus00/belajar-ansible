# Belajar Ansible

Run ping command:
```
ansible -i inventory.yml -m ping --ask-pass
```

Run script
```
ansible-playbook --ask-pass initial-setup.yml -i inventory.yml
```