#镜像基于tomcat:8-alpine创建
FROM tomcat:8-alpine

#Author
MAINTAINER wangqx <wangqx@chargerlink.com>

ADD dubbo.war /usr/local/tomcat/webapps/dubbo.war

EXPOSE 8080

CMD ["catalina.sh","run"]