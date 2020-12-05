cd <project dir>

docker run -it -v C:\Users\laco\Documents\SCHOOL\BIG\sem\work:/work -v C:\Users\laco\Documents\SCHOOL\BIG\sem\notebook:/usr/zeppelin/zeppelin-0.8.1-bin-all/notebook/ -p 18080:18080 -p 8088:8080 -d babubabu/spark-zeppelin-docker:v1

docker-compose up

access Kibana @localhost:5601
import json file from kibana/export