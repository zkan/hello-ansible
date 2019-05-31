# Hello, Ansible

```sh
ansible common -a pwd -i hosts --private-key=~/.ssh/some_private_key
```

## Removing hostname in `known_hosts`

```sh
ssh-keygen -R <hostname>
```
