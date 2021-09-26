# 10-monitoring-04-elk

root@ubuntu:/home/sergey/netology/ELK# docker ps
CONTAINER ID   IMAGE                                                  COMMAND                  CREATED             STATUS          PORTS                                                           NAMES
a9af81111b09   docker.elastic.co/beats/filebeat:7.2.0                 "/usr/local/bin/dock…"   13 minutes ago      Up 13 minutes                                                                   filebeat
1e900491561b   docker.elastic.co/kibana/kibana:7.11.0                 "/bin/tini -- /usr/l…"   13 minutes ago      Up 13 minutes   0.0.0.0:5601->5601/tcp, :::5601->5601/tcp                       kibana
4c4e26ece6d9   docker.elastic.co/logstash/logstash:6.3.2              "/usr/local/bin/dock…"   13 minutes ago      Up 13 minutes   5044/tcp, 9600/tcp, 0.0.0.0:5046->5046/tcp, :::5046->5046/tcp   logstash
b661920e07ed   docker.elastic.co/elasticsearch/elasticsearch:7.11.0   "/bin/tini -- /usr/l…"   13 minutes ago      Up 13 minutes   0.0.0.0:9200->9200/tcp, :::9200->9200/tcp, 9300/tcp             es-hot
4a5e3a820174   docker.elastic.co/elasticsearch/elasticsearch:7.11.0   "/bin/tini -- /usr/l…"   13 minutes ago      Up 13 minutes   9200/tcp, 9300/tcp                                              es-warm
773887a043df   python:3.9-alpine                                      "python3 /opt/run.py"    About an hour ago   Up 13 minutes 

![image](https://user-images.githubusercontent.com/67621467/134802006-c8b375a4-dda0-4a98-b7d2-1f4e4d98116e.png)
