FROM tomcat:9.0.5-jre8
COPY ./TalySetPinConfirmation.war /usr/local/tomcat/webapps
COPY ./ssl /usr/local/tomcat/ssl
COPY ./server.xml /usr/local/tomcat/conf
COPY ./tomcat-users.xml /usr/local/tomcat/conf
COPY ./context.xml /usr/local/tomcat/webapps/manager/META-INF