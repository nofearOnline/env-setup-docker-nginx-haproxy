# env-setup-docker-nginx-haproxy
deploy test enviorment of nginx and haproxy containers using ansible and docker

in this project i tried to deploy generic enviorment of haproxy lbs connecting to nginx servers with static content

you have three main playbooks:
setup.yml - set up the lbs and web containers on the hosts
update.yml - update the web image to the hosts image_name var
remove_web_server.yml - remove the web servers in the remove web group
