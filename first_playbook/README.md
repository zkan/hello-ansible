### Running Ansible Playbook

```sh
ansible-playbook -i hosts --private-key=./first_playbook playbook.yml -vv
```

### Creating SSH Key

```sh
ssh-keygen -t rsa -b 4096 -o -C "kan@prontomarketing.com"
```

### Creating a Vault

```sh
ansible-vault encrypt all
```

**Note:** Use Pronto123 as password.

### Running with Vault

```sh
ansible-playbook --ask-vault-pass -i hosts --private-key=./first_playbook playbook.yml -vv
```
