Student: Yaraslau Karotkin

Here is an algorithm of provision by ansible using roles

At first we know that tomcat includes jdk 1.7 dependecy, and it means that tomcat role should trigger java role as well.

We set up all roles of installing tomcat, nginx and jenkins
(based on previous *.yml)

We set up all inclusive files as (plugins jobs configs and etc to roles sources)

We set up these roles at our provisioning file provision.yml

![alt tag](https://github.com/MNTLab/cm-ansible-2/blob/yaraslau_karotkin/vagrant/ansible/screens/1.png)

![alt tag](https://github.com/MNTLab/cm-ansible-2/blob/yaraslau_karotkin/vagrant/ansible/screens/2.png)

![alt tag](https://github.com/MNTLab/cm-ansible-2/blob/yaraslau_karotkin/vagrant/ansible/screens/3.png)

![alt tag](https://github.com/MNTLab/cm-ansible-2/blob/yaraslau_karotkin/vagrant/ansible/screens/4.png)
