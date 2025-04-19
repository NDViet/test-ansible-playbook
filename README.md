Install Ansible

```bash
sudo apt install -y ansible-core
```

```bash
export $(cat .env | xargs)
```

Get start the playbook

```bash
ansible-playbook -i inventory playbook.yml
```
