# Cloud-native DevOps project

A Java web application (Maven, JSP) used as the base for a cloud-native DevOps pipeline on AWS. It was developed and built on an **EC2** instance.

## Structure
```
pom.xml                        Maven build (WAR packaging)
src/main/webapp/index.jsp      Web page
src/main/webapp/WEB-INF/       Deployment descriptor
```

## Build
```bash
mvn package    # → target/nextwork-web-project.war
```
Deploy the WAR to a servlet container (e.g. Tomcat).
