Created a CI/CD process using Jenkins where a static HTML website in Github is Deployed on to Docker container on and AWS ec2    instance through Ansible playbook. 
With every Push a developer makes it triggers a job in jenkins server that takes the latest version of html website from github and sends it to Ansible server where Ansible playbook is used to install docker on the client systems, 
create a docker image from dockerfile and run container and deploy website on apache containers.
Tools used: AWS EC2, Jenkins, Ansible, Github.
