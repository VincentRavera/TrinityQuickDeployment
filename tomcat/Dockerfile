FROM tomcat:8.0

MAINTAINER Vincent RAVERA <ravera.vincent@gmail.com>

ADD settings.xml /usr/local/tomcat/conf/
ADD tomcat-users.xml /usr/local/tomcat/conf/
RUN cp /mnt/*.war /usr/local/tomcat/webapps/
CMD ["catalina.sh", "run"]
