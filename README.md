# docker-collectd-snmp
Collectd snmp on docker

## test docker 
docker run -i --rm -t -v /tmp/app:/app pashi/collectd-snmp collectd -C /etc/collectd.conf.orig -f

## run app, config on /opt/switches/collectd.conf
docker run -d -t -v /opt/switches:/app pashi/collectd-snmp
