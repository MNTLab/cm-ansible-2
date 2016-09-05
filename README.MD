MTN.*NIX.11 Automated Environment Configuration Management
---

***Student***: [Aliaksei Khurhin](https://epa.ms/1Cqi0K)

Report
---

[My branch link] (https://github.com/MNTLab/cm-ansible-2/tree/aliaksei_khurhin)

Jenkins plugins are installed by downloading *.hpi files. Build job starts by token.

The effect of 'vagrant up' command is the same like in previous labwork, but inside it is made by ansible roles.
[Main playbook](/vagrant/ansible/provision.yml)
all default variables from roles can be redefined here. Java role is present like dependency of tomcat and jenkins role. Web role depends on tomcat and jenkins.

Links to roles' playbooks:
- [Java](/vagrant/ansible/roles/java/tasks/main.yml)
- [tomcat](/vagrant/ansible/roles/tomcat/tasks/main.yml)
- [jenkins](/vagrant/ansible/roles/jenkins/tasks/main.yml)
- [web](/vagrant/ansible/roles/web/tasks/main.yml)

[Vagrantfile](/vagrant/Vagrantfile) has commented provision section with local ansimble - can be usefull if it is impossible to install ansible on host machine.

![Alt Text](/resources/build_works.PNG "scr1")
![Alt Text](/resources/deploy_works.PNG "scr2")
![Alt Text](/resources/tomcat_works.PNG "scr3")
