# maven-war-creation
To generate a web page and building a war file, copy it into Tomcat webapp folder.
# Requirement:
Installation of Tomcat 9.0.100, Eclipse, Openjdk, Maven 3.9.9
# Must add maven 3.9.9 package bin folder in env variable path in order to run the mvn command
# Once the project is ready, run the following command:
```
mvn clean install
```
# Add Tomcat as a server to run
By clicking on Server tag and then add Tomcat to the build path by pointing to the installation directory
# Run the index.jsp file by right click on it and run as -> Run as Server
You will see your simple web page with localhost:8080/webapp/index.jsp
# Copy the webapp.war which is at the target folder into the Tomcat server webapp folder will do. 
Now, you can fire up your browser by going to Host_IP_Address:8080/webapp to view your web site.



