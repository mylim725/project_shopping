FROM tomcat:8.5.46-jdk8-openjdk

RUN rm -Rf /usr/local/tomcat/webapps/shopping-v1.0 ## tomcat root ��� ����
RUN rm -Rf /usr/local/tomcat/webapps/shopping-v1.0.war ## tomcat root ��� ����
COPY target/shopping-v1.0.war /usr/local/tomcat/webapps/shopping-v1.0.war