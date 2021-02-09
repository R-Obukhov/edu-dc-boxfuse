FROM tomcat:8.0-alpine

COPY target/hello-1.0.war /usr/local/tomcat/webapps/hello-1.0.war

ENV CATALINA_BASE /var/lib/tomcat8
ENV CATALINA_HOME /usr/local/tomcat

CMD ["catalina.sh", "run"]
