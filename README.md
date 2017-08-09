# devOps

The repository is exclusively created for devOps training.


Jenkins Configuration

- Create Users
- Add GithubIntegration Plugin in Jenkins
- Github Settings-> Integration & Services->Add Jenkins(Github plugin)
- For Jenkins hook URL, assign public IP from AWS to your local Jenkins


2. yum update 
3. wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat-stable/jenkins.repo 
4. rpm --import http://pkg.jenkins-ci.org/redhat-stable/jenkins-ci.org.key 
5. yum install jenkins 
6. service jenkins start 
7. chkconfig jenkins on 
8. Open your browser and navigate to http://<public DNS name or public IP of your VM>:8080 
Java Installation
1. sudo yum update 
2.sudo yum install java-1.8.0 
export PATH=/usr/lib/jvm/jre-1.8.0-openjdk.x86_64/bin:$PATH 
sudo yum remove java-1.7.0-openjdk 
[ec2-user@ip-172-31-33-240 ~]$ sudo update-alternatives --config java

There are 2 programs which provide 'java'.

  Selection    Command
-----------------------------------------------
*+ 1           /usr/lib/jvm/jre-1.7.0-openjdk.x86_64/bin/java
   2           /usr/lib/jvm/jre-1.8.0-openjdk.x86_64/bin/java

Enter to keep the current selection[+], or type selection number: 2
[ec2-user@ip-172-31-33-240 ~]$ sudo update-alternatives --config java

There are 2 programs which provide 'java'.

  Selection    Command
-----------------------------------------------
*  1           /usr/lib/jvm/jre-1.7.0-openjdk.x86_64/bin/java
 + 2           /usr/lib/jvm/jre-1.8.0-openjdk.x86_64/bin/java 
yum install git*
