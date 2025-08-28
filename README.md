# CI-CD-project
 Continuous Integration Using Jenkins, Nexus, Sonarqube &amp; Slack
Project2 :  Continuous Integration Using Jenkins, Nexus, Sonarqube & Slack
 
 
Before creating instances,

3 sg :Jenkins, sonarqube,nexus
Jenkins:8080,all traffic from sonarqube server to access Jenkins for quality gate result
Sonarqube: 9000, ngnix running on sonar server: open 80 (My IP), Jenkins upload reports to sonar server  (80)(custom)(Jenkins SG), 
Nexus: 8081, 8081 from Jenkins server as well (allows Jenkins server to upload artifact to nexus)


