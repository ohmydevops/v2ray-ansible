# v2ray-ansible
We are human beings, not slaves

# How to use?

1- Install ansible (minimum version: V2.13) -> https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#pip-install

2- Add your server's IP in inventory/hosts.ini file (mv .inventory/hosts.ini.example .inventory/hosts.ini) + and add your ssh user in hosts.ini

3- Add your custom varibles to vars.yaml (mv vars_example.yml vars.yml)

4- Finnaly Run this command: `ansible-playbook config-v2ray.yaml`
