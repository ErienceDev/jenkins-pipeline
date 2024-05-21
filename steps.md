1) ```
   docker run --rm -d --name jenkins -u root -p 8080:8080 -v jenkins-data:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock -v E:/azim/learn/docker/fod/ch07/jenkins-pipeline:/home jenkinsci/blueocean  
   ```
