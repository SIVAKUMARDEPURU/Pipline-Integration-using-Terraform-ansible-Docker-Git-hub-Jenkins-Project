# CI/CD pipeline integration by using terraform, ansible,Docker,Jenkins,cloudwatch
############################...SIVAKUMAR DEPURU...###################################
Install Java &Jenkins in your Amazon linux

Installation Steps :
Please launch an Amazon Linux instance using Amazon Linux AMI.
Login to your Amazon Linux instance.
Become root using “sudo su -” command.
Update your repositories
yum update
yum install java
Get Jenkins repository using below command
wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat-stable/jenkins.repo
Get Jenkins repository key
rpm --import http://pkg.jenkins-ci.org/redhat-stable/jenkins-ci.org.key
Install jenkins package
yum install jenkins
Start jenkins and make sure it starts automatically at system startup
Systemctl start jenkins
Systemctlenable jenkins
yum install git
Ansible Server Configuration{Docker and Ansible}
sudo amazon-linux-extras install ansible2
yum install docker
