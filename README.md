# logstash-config

This repository features default ELK and filebeat configuration that can be used to fully monitore Jahia Digital Experience 7+ installations. It contains Logstash patterns as well as Kibana dashboards.

These patterns have only been tested on Tomcat 8.

Requirements:
 * -XX:+PrintGCDateStamps should be added to tomcat/bin/setenv.sh in order to enhance Garbage Collection monitoring
