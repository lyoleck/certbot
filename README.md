# certbot
Certbot installation and configuration for CentOS or Ubuntu
  1. git clone this repository
  2. fill the domain variable, you can fill it even in your inventory file like this: hostname ansible_host=X.X.X.X domain=yourdomain
  3. use Ansible for example like this: ansible-playbook certbot.yml --limit hostname -i path/to/your/inventory
