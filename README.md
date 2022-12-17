# Continuous-Integration-jenkins

Cantinuous integration  Pipelin.Jenkins, Nexus &amp; Sonarqube Setup

Launch a Instance in Aws for Jenkins (Jenkinsserver)
1.Fist want to lAuch a instnce in Aws :-ubuntu 20  & ,Instance t2 small
2.Create a key pair 
3.Create Security Groups (add Rules port 22  from My Ip and port 8080 from my ip  and port 8080 allow from anywhere )
4.Under user data we want to put the script for jenkins (jenkinssetup.sh )
5.Launch instance 

Launch A instance for Nexus Server (Nexusserver)

1.Fist want to lAuch a instnce in Aws :-Centos7 & ,Instance t2 Medium 
2.Create a key pair 
3.Create Security Groups (add Rules port 22  from My Ip and port 8081 from anywhere and port 8080 allow from anywhere )
4.Under user data we want to put the script for Nexus (Nexussetup.sh )
5.Launch instance 

Launch A instance for sonarqube(Sonarserver)

1.Fist want to lAuch a instnce in Aws :-Ubuntu 18 & ,Instance t2 Medium 
2.Create a key pair 
3.Create Security Groups (add Rules port 22  from My Ip and port 80 from anywhere and port 9000 allow from anywhere )
4.Under user data we want to put the script for Sonarqube(Sonarsetup.sh )
5.Launch instance

Wait 10 minutes the  login in to each service then check the service status .
