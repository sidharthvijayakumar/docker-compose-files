Steps to run Jenkins.yml
-------------------------
1. Clone the repo in your local Visual studio code
2. Open terminal of vs code
3. cd jenkins
4. Then run the command 
     docker-compose -f jenkins.yml up
5. jenkins is configured on host port 8081 and container port 8080.
Hit http://localhost:8081
Jenkins password is present in the terminal or could get it by using exec command
    docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
ENJOY learning !
