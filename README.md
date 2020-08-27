# Ansible_project_for_Nginx
OS: Redhat

ansible play_book to setup nginx and run the service


- Install Ansible using sudo yum install -y ansible
- Create a new directory structure using the command . mkdir -p nginx_ansible/roles/nginx/tasks
- Create an Ansible role to install Nginx.
- Run the job.

## How to run
ansible-playbook -i Inventory  main.yaml

## How to test
input the below link into the browser.
http://ec2-3-106-136-9.ap-southeast-2.compute.amazonaws.com/

![home page]()
