FROM openjdk:8-jre-alpine
LABEL maintainer="Daniel Gresak (daniel.gresak@ucdconnect.ie)"
COPY target/webportal-0.0.1-jar-with-dependencies.jar /webportal-0.0.1-jar-with-dependencies.jar
CMD ["/usr/bin/java", "-cp", "/webportal-0.0.1-jar-with-dependencies.jar", "lf.webportal.WebPortalStart","-a","webportal","-p","2551","-h","webportal","-w","8080"]