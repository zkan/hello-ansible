### Running Ansible Playbook

```sh
ansible-playbook -i hosts --private-key=./first_playbook playbook.yml -vv
```

### Creating SSH Key

```sh
ssh-keygen -t rsa -b 4096 -o -C "kan@prontomarketing.com"
```
