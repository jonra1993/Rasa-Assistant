# Rasa-Assistant


 cheatsheet-> https://devhints.io/docker-compose
 docker -> https://devhints.io/docker
# Docker-compose commands
step1: docker-compose up -d
on a new temrinal: : sudo python3 rasa_x_commands.py create admin me MySecurePass

if that does not work: sudo python3 rasa_x_commands.py create --update admin me MySecurePass


step3: open localhost and enter password


docker exec -it ubuntu-server-container bash

# Connect PostgreSQL database using pgadmin
https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5

host: db_container_name
port: 5432
username: 
password: 


# Download config files 
https://storage.googleapis.com/rasa-x-releases/0.40.0a2/nginx-config-files/rasax.nginx.template
https://storage.googleapis.com/rasa-x-releases/0.40.0a2/nginx-config-files/nginx.conf
https://storage.googleapis.com/rasa-x-releases/0.40.0a2/nginx-config-files/ssl.conf.template



sudo python3 rasa_x_commands.py create admin me MySecurePass
sudo python3 rasa_x_commands.py create --update admin me MySecurePass


## Ansible

sudo ansible-galaxy install geerlingguy.docker
sudo ansible-playbook -i "localhost," -c local rasa_x_playbook.yml



./ngrok http 80
