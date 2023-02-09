FROM tomcat:9.0
RUN apt-get update
RUN apt-get install git -y
RUN mkdir /tmp/myvol/
RUN cp /tmp/myvol/* $CATALINA_HOME/webapps/
