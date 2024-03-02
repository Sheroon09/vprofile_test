## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql

  - `Execute SonarQube Scanner` > `Analysis properties`  (it is mandatary). 
   ```sh 
        sonar.projectKey=Sabear
	sonar.projectName=Sabear
	sonar.projectVersion=1.0
	sonar.sources=/var/lib/jenkins/workspace/$JOB_NAME/src/
	sonar.binaries=target/classes/com/visualpathit/account/controller/
	sonar.junit.reportsPath=target/surefire-reports
	sonar.jacoco.reportPath=target/jacoco.exec
	sonar.java.binaries=src/main/java/com/visualpathit/account/
     ```


