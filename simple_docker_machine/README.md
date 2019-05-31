# Hello, Ansible

Use an ad-hoc command:

```sh
ansible common -a pwd -i hosts --private-key=~/.ssh/some_private_key
```

Run a playbook:

```sh
ansible-playbook -i hosts --private-key=~/.ssh/rocket web.yml
```

Run a playbook without options (configure in `ansible.cfg`):

```sh
ansible-playbook web.yml
```

## Removing hostname in `known_hosts`

```sh
ssh-keygen -R <hostname>
```
