FROM tomcat:alpine
COPY target/*.war /usr/local/tomcat/webapps/new.war
EXPOSE 8080
CMD [“catalina.sh”, “run”]
