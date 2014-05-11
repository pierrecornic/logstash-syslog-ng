# Prerequisite

Logstash must be installed in /opt/logstash.

# Install

Copy logstash.init to /etc/init.d/logstash
chmod +x /etc/init.d/logstash
update-rc.d logstash defaults

Copy logstash-syslog.conf in /etc/logstash/logstash-syslog.conf
