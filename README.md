# cm-ansible-2
Task completed:

I have implemented 4 roles:
- [java](/vagrant/ansible/roles/java)  - [tasks/main.yml](/vagrant/ansible/roles/java/tasks/main.yml)
- [nginx](/vagrant/ansible/roles/nginx)  - [tasks/main.yml](/vagrant/ansible/roles/nginx/tasks/main.yml)
- [tomcat](/vagrant/ansible/roles/tomcat)  - [tasks/main.yml](/vagrant/ansible/roles/tomcat/tasks/main.yml)
- [jenkins](/vagrant/ansible/roles/jenkins)  - [tasks/main.yml](/vagrant/ansible/roles/jenkins/tasks/main.yml)


There are obviously lots of ways to improve the task:
 - creating additional variables to make roles more fersatile
 - adding environment state checks to ensure stability of the build
 - more handlers and options (java openjdk or oracle, versions etc)

But current roles state is pretty neat.

***Student***: [Dzmitry_Pasiukevich] (https://upsa.epam.com/workload/employeeView.do?employeeId=4060741400038670377#emplTab=general)

![Alt text](vagrant/ansible/resources/1.png "app")
![Alt text](vagrant/ansible/resources/2.png "jobs")
![Alt text](vagrant/ansible/resources/3.png "pipe")
