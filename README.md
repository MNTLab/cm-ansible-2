# Ansible HomeTask 2

In [provision.yml](/vagrant/ansible/provision.yml) is caused 3 roles, the 4th job (java) is caused by tomcat role.
There is 3 variables (ports numbers for all services) in provision.yml, wich also present in default directories of each roles. 

Roles:
 - [nginx](vagrant/ansible/roles/web). Main file in this role - [main.yml](vagrant/ansible/roles/web/tasks/main.yml)
 
 - [java](vagrant/ansible/roles/java). Main file in this role - [main.yml](vagrant/ansible/roles/java/tasks/main.yml)
 
 - [tomcat](vagrant/ansible/roles/tomcat). Main file in this role - [main.yml](vagrant/ansible/roles/tomcat/tasks/main.yml)
 
 - [jenkins](vagrant/ansible/roles/jenkins). Main file in this role - [main.yml](vagrant/ansible/roles/jenkins/tasks/main.yml)

Additional files:
 - [plugins for jenkins](vagrant/plugins/)
 - [jobs for jenkins](vagrant/jobs/)
 - [hudson.tasks.Maven.xml](vagrant/hudson.tasks.Maven.xml) - correct starting maven 
 - [jenkins-user](vagrant/jenkins-user) - add user rights
Screenshots of result: 
![1](https://github.com/MNTLab/cm-ansible-2/blob/Andrei_Kachan/resources/homer.png)
![0](https://github.com/MNTLab/cm-ansible-1/blob/Andrei_Kachan/resources/5.png)
![2](https://github.com/MNTLab/cm-ansible-2/blob/Andrei_Kachan/resources/jobs.png)
![3](https://github.com/MNTLab/cm-ansible-2/blob/Andrei_Kachan/resources/build_1.png)
![4](https://github.com/MNTLab/cm-ansible-2/blob/Andrei_Kachan/resources/build_2.png)
![5](https://github.com/MNTLab/cm-ansible-2/blob/Andrei_Kachan/resources/build_3.png)
![6](https://github.com/MNTLab/cm-ansible-2/blob/Andrei_Kachan/resources/deploy.png)

   

