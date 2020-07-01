# docker-ansible
# docker-ansible Instructions

#Run the following commands in your teminal as ROOT or using "sudo"

sudo apt update -y

sudo apt install ansible -y

#Install OpenSSH-Server in case you want to connecto you machine remotely with an SSH client
sudo apt install openssh-server -y

#Then pull this repository:

sudo git clone https://github.com/trainerboris/docker-ansible.git

cd docker-ansible/

sudo ansible-playbook docker.yml

