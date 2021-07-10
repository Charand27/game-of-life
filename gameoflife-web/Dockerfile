FROM tomcat
MAINTAINER charan
RUN mv webapps webapps2
RUN mv webapps.dist/ webapps
COPY target/gameoflife.war /usr/local/tomcat/webapps
CMD ["catalina.sh","run"]
