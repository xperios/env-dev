# env-dev

```
curl ${ANSIBLE_HOSTS_CURL} >> ansible/hosts.yml
pip install ansible
ansible-playbook ansible/deploy.yml -i ansible/hosts.yml
```
