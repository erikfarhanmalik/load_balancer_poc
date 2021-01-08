FROM tomcat:8.5.50-jdk8-openjdk
LABEL maintainer="erikfarhan@deltadatamandiri.com"
COPY redis_session_poc.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
