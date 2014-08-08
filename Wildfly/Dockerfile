FROM jboss/wildfly

RUN /opt/wildfly/bin/add-user.sh --user admin --password qwerty1! --enable

CMD /opt/wildfly/bin/standalone.sh -b 0.0.0.0 -bmanagement 0.0.0.0
