In this task I created next roles:
 - [nginx](/vagrant/ansible/roles/nginx). Main file in this role - [main.yml](/vagrant/ansible/roles/nginx/tasks/main.yml)
 - [java](/vagrant/ansible/roles/java) - Main file in this role - [main.yml](/vagrant/ansible/roles/java/tasks/main.yml)
 - [tomcat](/vagrant/ansible/roles/tomcat) - Main file in this role - [main.yml](/vagrant/ansible/roles/tomcat/java/main.yml)
 - [jenkins](/vagrant/ansible/roles/jenkins) - Main file in this role - [main.yml](/vagrant/ansible/roles/jenkins/java/main.yml)
 
In [provision.yml](/vagrant/ansible/provision.yml) I call only 3 roles, because 4th job (java) is called by tomcat role.
There is 4 variables (ports numbers for all services and version of java) in provision.yml, wich also present in default directories of each roles. 

Screenshots of result: 
![alt text](https://github.com/MNTLab/cm-ansible-2/blob/anton_tkachenka/screenshots/1.png "http://localhost/sample")
![alt text](https://github.com/MNTLab/cm-ansible-2/blob/anton_tkachenka/screenshots/2.png "http://localhost/sample")
![alt text](https://github.com/MNTLab/cm-ansible-2/blob/anton_tkachenka/screenshots/2-2.png "http://localhost/sample")
![alt text](https://github.com/MNTLab/cm-ansible-2/blob/anton_tkachenka/screenshots/3.png "http://localhost/sample")
![alt text](https://github.com/MNTLab/cm-ansible-2/blob/anton_tkachenka/screenshots/4.png "http://localhost/sample")
![alt text](https://github.com/MNTLab/cm-ansible-2/blob/anton_tkachenka/screenshots/5.png "http://localhost/sample")
