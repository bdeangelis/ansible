# ansible
## Getting Started

### Ansible Setup  
Install pip  
`sudo apt-get install python-pip`  
Install Ansible Dependencies  
`sudo pip install python-dev paramiko PyYAML Jinja2 httplib2 six sudo`  
Install Ansible 
`sudo pip install ansible`  
Install Git  
`sudo add-apt-repository ppa:git-core/ppa`  
`sudo apt-get update`  
`sudo apt-get install git`  
Verify connection to Git 
`ssh -T git@github.com`  
If you get 'Permission denied (publickey).'
Verify that ssh is running
`eval "$(ssh-agent -s)"`  
verify that ssh is available  
`ssh-add -l` --lists all ssh keys
`ssh-add <path_to_key>` --if no keys listed
Clone Ansible Repo  
`git clone https://github.com/bdeangelis/ansible.git`

### Staging Setup  
Create RDS Instance  
Create EC2 Instance  
Create LoadBalancer  
Add RDS Info to Staging Varable File  
Add EC2 Info to Staging Variable File  

### Dev Setup  
