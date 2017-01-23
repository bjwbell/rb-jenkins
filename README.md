# rb-jenkins
Jenkins Pipeline for rb project, https://github.com/timohanke/rb.

## jenkins ssh credentials

1. Login as the jenkins user
```
    sudo su -s /bin/bash jenkins
```
2. Create .ssh directory and files
```
    cd /var/lib/jenkins
    mkdir .ssh
```
3. Add Jenkins to Docker group

   http://stackoverflow.com/questions/38105308/jenkins-cant-connect-to-docker-daemon#38109447
