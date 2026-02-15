# VPS Playbook
Deploying - Shadowsocks, MTProto, Fail2ban, Node Exporter  

# Usage:  
```sh
echo "hostname ansible_host=1.1.1.1 ansible_user=root" >> inventory.ini
ansible-playbook -i ./inventory.ini --extra-vars="hosts=hostname" main.yml
```