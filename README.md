## Install my flask app
ansible-playbook -i hosts.ini setup_wp.yaml\

### Load balancer
- install epel
- install nginx
- put nginx conf
- reload nginx

### flask_app
- REPO: https://github.com/kudseb/flaskprototype
- install python
- sync repo
- create user (currently usseles)
- Install virtualenv via pip (just to be sure)
- create venv and install packages
- put systemd cfg
- start service

![alt text](https://github.com/kudseb/ansibleflaski/blob/main/Screenshot%202022-01-11%20093311.png?raw=true)
