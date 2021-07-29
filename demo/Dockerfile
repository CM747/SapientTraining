FROM tomcat:9-slim
USER root
WORKDIR /usr/local/tomcat/webapps/
ARG WAR_FILE=target/*.war
ADD ${WAR_FILE} /usr/local/tomcat/webapps/
EXPOSE 8080
#docker build -t web-server .
#docker run -d -p 9090:8080 web-server
