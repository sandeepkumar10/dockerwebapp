FROM tomcat:8-jre11

LABEL maintainer="Sandeep Kumar"
LABEL description="dockerwebapp for production"

WORKDIR /usr/local/tomcat/

EXPOSE 8080

RUN rm -rf ./webapps/*

COPY target/vprofile-v2.war ./webapps/ROOT.war

CMD ["catalina.sh", "run"]
