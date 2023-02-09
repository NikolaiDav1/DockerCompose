FROM tomcat:9.0
RUN apt-get update
RUN apt-get install git -y
RUN mkdir /tmp/myvol/ && touch /tmp/myvol/mycalcwebapp.war
RUN cp /tmp/myvol/* $CATALINA_HOME/webapps/
