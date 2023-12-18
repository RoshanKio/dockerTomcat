# Use the official Tomcat base image
FROM tomcat:latest

# Copy your War file into the webapps directory of Tomcat
COPY app1.war /usr/local/tomcat/webapps/

# Optionally, you can expose the default Tomcat port
EXPOSE 8080

ENV MY_NAME Roshan

# Start Tomcat when thener starts
CMD ["catalina.sh", "run"]  
