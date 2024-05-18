# Archlinux setup with Ansible


## 1. Install ansible
```
./install
```

## 2. Run the script
```
ansible-playbook  local.yml --become-password-file .become-password --vault-password-file .vault
```
