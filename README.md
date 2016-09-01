Student: Yauheni Likhachou

Home Task Ansible2

1. Created [yml-file](vagrant/ansible/provision.yml)

2. Created configs files:
   
   2.1. [config.xml](vagrant/ansible/configs/config.xml )

   2.2. [default.conf](vagrant/ansible/configs/default.conf)

   2.3. [jenkins](vagrant/ansible/configs/jenkins)

   2.4. [server.xml](vagrant/ansible/configs/server.xml)

   2.5. [Maven.xml](vagrant/ansible/configs/hudson.tasks.Maven.xml)

   2.6. [jenkins-user](vagrant/ansible/configs/jenkins-user)

   2.7. [sudoers](vagrant/ansible/configs/sudoers)

3. Created 2 jobs:

   3.1.[Build](vagrant/ansible/configs/jobs/build/config.xml)

   3.2.[Deploy](vagrant/ansible/configs/jobs/deploy/config.xml)

4. Created [http://localhost:8080/jenkins](sources/Screenshot-1.png)

5. Created [http://localhost:8080/mnt-lab](sources/Screenshot.png)

6. [Vagrantfile](vagrant/Vagrantfile)

7. Added task-roles files: 
   
   7.1. Tomcat: [main.yml](vagrant/ansible/roles/tomcat/tasks/main.yml)
	
   7.2. Nginx: [main.yml](vagrant/ansible/roles/web/tasks/main.yml)

   7.3. Jenkins: [main.yml](vagrant/ansible/roles/jenkins/tasks/main.yml)

   7.4. Java: [main.yml](vagrant/ansible/roles/java/tasks/main.yml)

## Task Report Notes

![](/sources/Screenshot.png)
![](/sources/Screenshot-1.png)
![](/sources/Screenshot-2.png)
![](/sources/Screenshot-3.png)
![](/sources/Screenshot-4.png)


