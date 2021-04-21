    1  docker pull infracloudio/csvserver:latest
    2  docker images
    3  docker pull prom/prometheus:v2.22.0
    4  docker images
   34  vi gencsv.sh
   35  ls -lrt
   51  echo $RANDOM
  111  cat gencsv.sh 
  139  vim gencsv.sh 
  140  ./gencsv.sh 4
  162  ./gencsv.sh 
  169  ls -lrt
  190  docker ps -a
  214  VAR1="${1:-10}"
  244  docker run -d -v /csvserver/solution/inputFile:/csvserver/inputdata infracloudio/csvserver
  256  docker exec -it b9
  257  docker exec -it b9 /bin/bash
  267  docker ps -a
  269  curl http://localhost:9393
  270  docker exec -it ff /bin/bash
  271  docker ps -a
  272  docker stop ff
  273  docker rm ff
  274 docker run -itd -p 9393:9300 -v /root/csvserver/solution/inputFile:/csvserver/inputdat -e CSVSERVER_BORDER='Orange' infracloudio/csvserver
  276 curl http://localhost:9393
  278 pwd
