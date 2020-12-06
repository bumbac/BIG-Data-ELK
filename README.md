Clone this repository to your project path.

Download datafiles to "your project path"/work.


`cd "your project path"`


`docker run -it -v "your project path"/work:/work -v "your project path"/notebook:/usr/zeppelin/zeppelin-0.8.1-bin-all/notebook/ -p 18080:18080 -p 8088:8080 -d babubabu/spark-zeppelin-docker:v1`


`docker-compose up`


After all containers are up:
1. Access zeppelin notebook @ http://localhost:8088/
2. Access Kibana @ http://127.0.0.1:5601/
3. Create index from global
4. Go to Managment/Save Objects/Import
5. Use index global
6. Import all objects from "your project path"/kibana/export/export.json



EXAMPLE:

`cd C:\Users\laco\Documents\SCHOOL\BIG\sem`


`docker run -it -v C:\Users\laco\Documents\SCHOOL\BIG\sem\work:/work -v C:\Users\laco\Documents\SCHOOL\BIG\sem\notebook:/usr/zeppelin/zeppelin-0.8.1-bin-all/notebook/ -p 18080:18080 -p 8088:8080 -d babubabu/spark-zeppelin-docker:v1`

`docker-compose up`

