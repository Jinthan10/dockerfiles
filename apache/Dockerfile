
FROM tomcat:latest
ENV CATALINA_HOME /usr/local/tomcat
ENV CATALINA_BASE /usr/local/tomcat
COPY your-app.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
