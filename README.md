MTN.*NIX.11 Automated Environment Configuration Management
---

***Student***: Roman_Kalinyuk

[Roman_Kalinyuk] (https://epa.ms/1Cqq0e) Ansible Home Task 2
---

Now it is implemented 4 separated roles in [provision.yml](/vagrant/ansible/provision.yml), each in own config file:
(4th role _java_ is called by tomcat role)
- [java](/vagrant/ansible/roles/java)  - [tasks/main.yml](/vagrant/ansible/roles/java/tasks/main.yml)
- [nginx](/vagrant/ansible/roles/web)  - [tasks/main.yml](/vagrant/ansible/roles/web/tasks/main.yml)
- [tomcat](/vagrant/ansible/roles/tomcat)  - [tasks/main.yml](/vagrant/ansible/roles/tomcat/tasks/main.yml)
- [jenkins](/vagrant/ansible/roles/jenkins)  - [tasks/main.yml](/vagrant/ansible/roles/jenkins/tasks/main.yml)

There are 4 variables (ports numbers for all services and version of java) in provision.yml, wich also present in default directories of each role.

![1] (https://github.com/MNTLab/cm-ansible-2/blob/roman_kalinyuk/resources/Jenkins-Jobs.png)

![2] (https://github.com/MNTLab/cm-ansible-2/blob/roman_kalinyuk/resources/Job01Build.png)

![3] (https://github.com/MNTLab/cm-ansible-2/blob/roman_kalinyuk/resources/Job02Deploy.png)

![4] (https://github.com/MNTLab/cm-ansible-2/blob/roman_kalinyuk/resources/BuildPipelining.png)

![5] (https://github.com/MNTLab/cm-ansible-2/blob/roman_kalinyuk/resources/Fin.png)

