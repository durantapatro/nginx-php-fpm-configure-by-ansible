# ansible-playbooks

# Clone Repo:
```bash
git clone https://github.com/durantapatro/ansible-playbooks.git
```
# Apply Read Permission to ansible_key.pem file.
```bash
chmod 400 ansible_key.pem
```
# Then Run Ansible Command
```bash
ansible-playbook -i inventory/hosts playbooks/nginx-php7.4-fpm-playbook.yaml
ansible-playbook -i inventory/hosts playbooks/proxysql-configure-playbook.yaml
```